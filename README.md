# crename

crename is a simple bash script for converting all files in a directory into a different file extension. For example maybe you want to change all JPEGs in a folder into PNGs. 

## Installation

```bash
git clone (https://github.com/APEFOOD/crename.git) && cd crename 

chmod +x crename 

# make the script available globally
sudo mv crename /usr/local/bin/crename 

```
## Usage

```bash
# convert every jpeg in the directory into a png
crename -i jpeg -o png

```

## Contributing

Pull requests are welcome.

## License

[MIT](https://choosealicense.com/licenses/mit/)