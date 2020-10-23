# reviveall

Reviveall is an plugin for FiveM [ESX] with features:

- Allows You To Revive All Dead Players

## Requirements

   - [esx_ambulancejob](https://github.com/esx-framework/esx_ambulancejob)

## Download & Installation

### Using [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx Mqasim14/reviveall
```

### Using Git
```
cd resources
git clone https://github.com/Mqasim14/reviveall [esx]/reviveall
```

### Manually
- Download https://codeload.github.com/Mqasim14/reviveall/zip/main
- Put it in the `[esx]` directory

## Installation
- You May Need To Change Line 22 To Match Your Trigger If You Have Changed It
- YOu Can also Change The Ace Used On Line 16
- Add this in your `server.cfg`:

```
start reviveall
add_ace insertgrouporidentifierhere reviveall allow	

Example:

add_ace group.admin reviveall allow	
add_ace identifier.steam:inserthex reviveall allow
```
