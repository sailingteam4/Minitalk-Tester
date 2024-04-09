# 42 Minitalk Tester

This is a simple tester for the 42 Minitalk project. It is designed to test the project with a variety of different inputs and edge cases to ensure that it is functioning correctly.

## Installation

This repo only contains `test.py` so you can launch it with one command !

```sh
curl https://raw.githubusercontent.com/sailingteam4/Minitalk-Tester/main/tester.py > tester.py && python3 tester.py
```

Or you can clone the repo and run the script from there.

```sh
git clone https://github.com/sailingteam4/Minitalk-Tester.git
cd Minitalk-Tester
python3 tester.py
```

## Requirements

This script requires a recent version of Python3 to run correctly. It also requires basic c development tools such as gcc and make to compile the project, and the Norminette to check the code.

## Usage

This script tests the Makefile, checks the Norminette, verifies the existence of `./server` and `./client`, and tests the communication between `./server` and `./client`. It also runs a series of parsing tests.

## Contributing

Pull requests are welcome. If you would like to contribute to this project, please open an issue first to discuss what you would like to change.
