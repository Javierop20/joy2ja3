![pythonver](https://img.shields.io/badge/python-3-blue.svg)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
# joy2ja3
Python tool for converting from joy format to JA3 format SSL/TLS hashes

## Getting Started

1. Clone this repository

```buildoutcfg
git clone https://github.com/Javierop20/joy2ja3.git
```

2. Enter the folder and start using the tool

```buildoutcfg
cd joy2ja3/
python3 joy2ja3.py --help
```

## Usage

```buildoutcfg
$ python3 joy2ja3.py <File in Joy JSON Format>
```

## Example

```buildoutcfg
$ python3 joy2ja3.py example.json
Do you want the raw JA3 fingerprints? [y/n] (default n) y
['ce5f3254611a8c095a3d821d44539877', 'bca93cb3e8c593b8f50931a101bd0635', '53fccecd410c6aacaceb9533c5bb9216', 'e4d448cdfe06dc1243c1eb026c74ac9a', 'b20b44b18b853ef29ab773e921b03422']
['771,49196-49195-49200-49199-159-158-49188-49187-49192-49191-49162-49161-49172-49171-157-156-61-60-53-47-10,0-5-10-11-13-35-23-65281,29-23-24,0', '771,2570-4865-4866-4867-49195-49199-49196-49200-52393-52392-49171-49172-156-157-47-53-10,2570-0-23-65281-10-11-35-16-5-13-18-51-45-43-27-2570-21,2570-29-23-24,0', '771,49200-49196-49199-49195-49192-49188-49191-49187-157-156-60-255,0-11-10-35-13-15,25-24-23-19,0-1-2', '771,255-49196-49195-49188-49187-49162-49161-49160-49200-49199-49192-49191-49172-49171-49170-157-156-61-60-53-47-10,0-10-11-13-5-18-23,23-24-25,0', '771,4865-4867-4866-49195-49199-52393-52392-49196-49200-49162-49161-49171-49172-51-57-47-53-10,0-23-65281-10-11-35-16-5-51-43-13-45-28-21,29-23-24-25-256-257,0']
```

## TODO

- Create database of JA3 hashes and merge it with the JA3er Database
- Fix bugs 
