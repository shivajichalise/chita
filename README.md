# chita 

> NOTE: it requires [CSVkit](https://csvkit.readthedocs.io/en/latest/) to run and uses GNU Core Utilities commands `sed`, `head`, `tail`, `awk`, `cut`, `paste` etc.

```sh
pacman -S csvkit
apt install csvkit
```

## Installing

For the current user:

```sh
curl https://raw.githubusercontent.com/shivajichalise/chita/main/chita > ~/usr/local/bin/chita && chmod +x ~/usr/local/bin/chita
```

Or simply copy the `chita` file to a location in your `$PATH` and make it executable.

## Usage

- run ./chita <***spreadsheet***> <***sheet_name***> <***program***> <***semester in roman numeral***>
- example: ./chita Exam_PU.xlsx BE_IT_CE "Bachelor of Software Engineering" V
- done

> NOTE: this script only works (**finger crossed**) for examination routine published by Pokhara University

## Self-Promotion

Star the repository on [Github](https://github.com/shivajichalise/chita)
Follow [shivajichalise](http://shivajichalise.com.np) on [Github](https://github.com/shivajichalise)

## License

This project is licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
