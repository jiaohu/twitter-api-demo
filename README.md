# X Api Demo
This is a demo for user to request with twitter api, use the sdk [twitter-v2](https://crates.io/crates/twitter-v2)

### Pre-Work
here, wo should register to be a developer for X(twitter), then you should set the user authentication
<img width="1019" alt="image" src="https://github.com/jiaohu/twitter-api-demo/assets/13608671/21958c88-1193-483c-8a6d-6605dcba8165">



<img width="655" alt="image" src="https://github.com/jiaohu/twitter-api-demo/assets/13608671/a58cd181-88ae-4c00-a580-c2db23bcb5a8">


**Attention that, the app info for `Callback URI / Redirect URL` must set and copy it to the `main` function in `src/main.rs`**

### Run the work

#### env
first you should add the `.env` file in the root path. The detail shown in the file `.env.example`

```shell
CLIENT_ID= # twitter client id
CLIENT_SECRET= # client secret
RUST_LOG= # debug, info, .e.g
```

#### command
```
cargo run
```
