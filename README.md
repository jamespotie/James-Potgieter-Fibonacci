# James-Potgieter-Fibonacci

The program presented in used to find the index of the first term of the Fibonacci sequence to contain a user-specified number of digits.

## Installation

1) Download the compressed tarball JamesPotgieter.tar.gz of the Docker build directory.
2) Extract the files required to build the container using a command prompt as shown below:

```command
tar -xzvf JamesPotgieter.tar.gz
```
3) The files needed for the container build are extracted to the current directory.
4) Build the container using a powershell terminal as shown below:

```powershell
docker build -t fibonacci-term .
```

## Usage

```powershell
$ docker run --rm fibonacci-term 2
>>
7
$ docker run --rm fibonacci-term 3
>>
12
$ docker run --rm fibonacci-term 10
>>
45
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
