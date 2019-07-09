# TOTP generator

## Setup

Install dependencies:
```
pip3 install pyotp
```

Add to your PATH (optional)
```
ln -s ~/Projects/totp/totp ~/.local/bin/totp
```

## Usage

For help:
```
totp -h
```

To generate an 8 digit code SHA512
```
totp OYQFMNRNDUWDODDA
```