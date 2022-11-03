# James-Potgieter-Fibonacci

The program presented in used to find the index of the first term of the Fibonacci sequence to contain a user-specified number of digits.

## Requirements

1) Docker Desktop installed and running locally.
2) Command prompt installed and running locally.
3) Windows PowerShell installed and running locally.

## Installation

1) Download the compressed tarball JamesPotgieter.tar.gz of the Docker build directory.
2) Navigate to the appropriate directory and extract the files required to build the container using a command prompt as shown below:

```command
$ tar -xzvf JamesPotgieter.tar.gz
```
3) The files needed for the container build, Dockerfile and main.py, are extracted to the current directory.
4) Navigate to the appropriate directory and build the container using a PowerShell terminal as shown below:

```powershell
$ docker build -t fibonacci-term .
```

## Usage
Once the container has been built, it will be present as an image in Docker Desktop and the program can be executed using a PowerShell terminal as follows:
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
