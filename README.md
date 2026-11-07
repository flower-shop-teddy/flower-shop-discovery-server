# flower-shop-discovery-server

Eureka server, nơi các service đăng ký và tìm nhau.

Cổng local: `8761`

## Chạy

Cách khuyên dùng: chạy cả hệ thống từ repo `flower-shop-workspace` (`./clone-all.sh` rồi `./run-local.sh`).

Build riêng repo này:

```bash
mvn verify
```

Cần parent `com.flowershop:flower-shop-parent` từ repo `flower-shop-platform`: nằm sẵn ở `../platform` trong workspace,
hoặc đã `mvn install` vào `~/.m2`.
