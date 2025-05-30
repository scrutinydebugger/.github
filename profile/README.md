# Scrutiny Debugger

### An open source debugging, development and testing tool for C/C++ embedded applications that works through instrumentation.
### Details at https://scrutinydebugger.com

## Repos

- **scrutiny-main** : Python package including :
  1. Scrutiny server
  2. The CLI and the postbuild tools
  3. The Python SDK client
  4. A QT GUI based on PySide6

- **scrutiny-embedded** : The C++ instrumentation library meant to be included in your firmware
- **scrutiny-demos** : A collection of example projects that use Scrutiny
- **scrutiny-devtools** : Some internal tools used for the development of Scrutiny
- **scrutiny-website** : The source code of scrutinydebugger.com 

## Architecture

<img src="/profile/assets/global_architecture.png" alt="Scrutiny architecture" width="800"/>

