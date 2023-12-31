# Keeper Web

If you want to start project right away, you might want to try the following commands:

```bash
cd dkeeper/
dfx help
dfx config --help
```

## Running the project locally

If you want to test project locally, you can use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, your application will be available at `http://localhost:8000?canisterId={asset_canister_id}`.

Additionally, if you are making frontend changes, you can start a development server with

```bash
npm start
```

Which will start a server at `http://localhost:8080`, proxying API requests to the replica at port 8000.
