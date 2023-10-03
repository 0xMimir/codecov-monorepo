# Codecov monorepo

This project is example of using codecov for code coverage on monorepo, this project include two simple projects one in rust with code coverage of 50% and smart-contract project written in solidity and typescript with 100% code coverage.

You can see code coverage per project here:

Rust api: [![codecov](https://codecov.io/gh/0xMimir/codecov-monorepo/graph/badge.svg?flag=rust-api)](https://codecov.io/gh/0xMimir/codecov-monorepo)

Smart contract: [![codecov](https://codecov.io/gh/0xMimir/codecov-monorepo/graph/badge.svg?flag=smart-contract)](https://codecov.io/gh/0xMimir/codecov-monorepo)


When uploading code coverage to codecov you must specify flag with `-F` in this case, rust api uploads with `-F rust-api` and smart contract uploads with `-F smart-contract` then you need to enable flags in your app at [codecov](https://app.codecov.io). Badge for whole monorepo can be found regular badge url:
```
https://codecov.io/gh/{your username}/{your project}/graph/badge.svg
```

And to see for inner projects add `flag` param to badge, so for smart contract add `flag=smart-contract`
```
https://codecov.io/gh/0xMimir/codecov-monorepo/graph/badge.svg?flag=smart-contract
```

and for api add `flag=rust-api`
```
https://codecov.io/gh/0xMimir/codecov-monorepo/graph/badge.svg?flag=smart-contract
```