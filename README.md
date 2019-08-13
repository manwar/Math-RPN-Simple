# Math::RPN::Simple

![Made with Perl](https://img.shields.io/badge/made%20with-perl-0.svg?color=cc2020&labelColor=ff3030&style=for-the-badge)
![Made with Batch](https://img.shields.io/badge/made%20with-batch-0.svg?color=cc2020&labelColor=ff3030&style=for-the-badge)

![GitHub](https://img.shields.io/github/license/DeBos99/Math-RPN-Simple.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/DeBos99.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/DeBos99/Math-RPN-Simple.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/DeBos99/Math-RPN-Simple.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub watchers](https://img.shields.io/github/watchers/DeBos99/Math-RPN-Simple.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/DeBos99/Math-RPN-Simple.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)

![GitHub commit activity](https://img.shields.io/github/commit-activity/w/DeBos99/Math-RPN-Simple.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/DeBos99/Math-RPN-Simple.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/DeBos99/Math-RPN-Simple.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/DeBos99/Math-RPN-Simple.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)

![GitHub issues](https://img.shields.io/github/issues-raw/DeBos99/Math-RPN-Simple.svg?color=cc2020&labelColor=ff3030&style=for-the-badge)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/DeBos99/Math-RPN-Simple.svg?color=10aa10&labelColor=30ff30&style=for-the-badge)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NH8JV53DSVDMY)

**Math::RPN::Simple** is simpler implementation of [Math::RPN](https://metacpan.org/pod/Math::RPN).

## Content

- [Content](#content)
- [Installation](#installation)
  - [Windows](#windows)
  - [Unix](#unix)
    - [Debian/Ubuntu](#apt)
    - [Arch Linux/Manjaro](#pacman)
    - [CentOS](#yum)
    - [MacOS](#homebrew)
- [Documentation](#documentation)
  - [Methods](#methods)
  - [Operators](#operators)
  - [Functions](#functions)
- [Authors](#authors)
- [Contact](#contact)
- [License](#license)

## Installation

### Windows

* Install [Git](https://git-scm.com/download/win).
* Install [Perl](http://strawberryperl.com/).
* Run following command in the command prompt:
```
cpan -i Math::RPN::Simple
```

### Unix

#### <a name="APT">Debian/Ubuntu based

* Run following commands in the terminal:
```
sudo apt install git perl -y
cpan -i Math::RPN::Simple
```

#### <a name="Pacman">Arch Linux/Manjaro

* Run following commands in the terminal:
```
sudo pacman -S git perl --noconfirm
cpan -i Math::RPN::Simple
```

#### <a name="YUM">CentOS

* Run following commands in the terminal:
```
sudo yum install git perl -y
cpan -i Math::RPN::Simple
```

#### <a name="Homebrew">MacOS

* Run following commands in the terminal:
```
brew install git perl
cpan -i Math::RPN::Simple
```

## Documentation

## Methods

| Method                       | Description                                       |
| :--------------------------- | :------------------------------------------------ |
| to_infix(expression)         | Returns infix representation of **expression**.   |
| to_postfix(expression)       | Returns postfix representation of **expression**. |
| evaluate_infix(expression)   | Returns value of infix **expression**.            |
| evaluate_postfix(expression) | Returns value of postfix **expression**.          |

## Operators

* \+
* \-
* \*
* /
* \**

## Functions

| Function | Description                          |
| :------- | :----------------------------------- |
| abs(x)   | Returns absolute value of **x**.     |
| int(x)   | Returns int representation of **x**. |

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos99](https://github.com/DeBos99)

## Contact

* Discord: DeBos#3292
* Reddit: [DeBos99](https://www.reddit.com/user/DeBos99)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
