### 1. How to install

```sh
$ git clone https://github.com/soosap/currency-converter.git
$ yarn install
```

### 2. How to run
```sh
$ yarn start
# alternatively start w/ react-native-debugger
$ REACT_DEBUGGER="unset ELECTRON_RUN_AS_NODE && open -g 'rndebugger://set-debugger-loc?port=19001' ||" yarn start
# alternatively start w/ react-native-debugger on specific platform
$ REACT_DEBUGGER="unset ELECTRON_RUN_AS_NODE && open -g 'rndebugger://set-debugger-loc?port=19001' ||" react-native run-ios
```