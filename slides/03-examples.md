# A (Contrived) Example

```php [1-4|1-10|12-13]
/** DFI */
interface CanSpeak {
    public function speak(): string;
}

/** DFI */
interface TreatAware {
    public function doTrick(): void;
    public function getTreat(): void;
}

/** ARI */
interface Pet extends CanSpeak, TreatAware {}
```

***

# A (More Realistic) Example

```php [1-9|11-13]
/** DFI */
interface CanHandleDataModel {
    public function load(mixed $key): DataModel;
    public function save(DataModel $data): void;
}
interface HasConnection {
    public function connect(): void;
    public function disconnect(): void;
}

/** ARI */
interface DataRepository extends CanHandleData, HasConnection {}
interface MemoryCache extends CanHandleData {}
```

***

# Some Real Examples

- DFI
  - `JsonSerializable`
  - `Countable`
  - `Stringable`
  - `Psr\Log\LoggerAwareInterface`
  - `Illuminate\Contracts\Auth\Authenticatable`
  - Most of `Illuminate\Contracts\Support`
- (Almost) ARI
  - `Psr\Container\ContainerInterface`
  - `Psr\Log\LoggerInterface`
  - ...literally hundreds more
