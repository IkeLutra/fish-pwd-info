# fish-pwd-info

Print easy-to-parse information about the current working directory.

## Installation

With [Fisher](https://github.com/jorgebucaran/fisher)

```
fisher add fishpkg/fish-pwd-info
```

## Usage

```console
pwd_info [SEPARATOR]
```

In a regular directory.

```fish
cd path/to/my/dir
pwd_info /
```

```console
dir
p/t/my
↵
```

Inside a git repository.

```fish
cd path/to/git/repo/sub/dir
pwd_info " "
```

```console
repo
p t g
sub dir
```

## License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
