## Ethereum Wallet for [ERC20](https://en.wikipedia.org/wiki/ERC-20) smart contracts.

The idea is to have a boiler plate to transfer tokens from one address to another based on smart contracts. Further it can connect to any RPC server or your Local geth node. This app is fully functional.

### What's in here

- Built in [Flutter](https://flutter.dev/docs/get-started/install)
- [Google ML Vision](https://firebase.google.com/docs/ml-kit) for QRCode scan.
- [Web3Dart](https://github.com/simolus3/web3dart) to interact with Ethereum blockchain
- [mobx.dart](https://github.com/mobxjs/mobx.dart) for state management

### Building Stores (Codegen)

Build - `flutter packages pub run build_runner build`

Watch - `flutter packages pub run build_runner watch`

### Running

- Change the abi.json in contract.dart
- Change the name of your functions in Hyper ledger or Smart Contracts.
- Txn ID of Ledger
- RPC URL
- flutter pub get packages
- flutter run

