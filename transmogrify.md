These are the Vim commands applied to the 'base16-solarized' colour scheme files in order to transmogrify them into the carbonized files.

The carbonized colour scheme files found in this repository are generated from:

- [`base16-solarized-light.vim`](https://github.com/chriskempson/base16-vim/blob/master/colors/base16-solarized-light.vim) commit c1c3e6c
- [`base16-solarized-dark.vim`](https://github.com/chriskempson/base16-vim/blob/master/colors/base16-solarized-dark.vim) commit c1c3e6c

## names

```
%s/base16-default-light/carbonized-light/
```

```
%s/base16-default-dark/carbonized-dark/
```

## main

```
3 | d4 |


%s/181818/2b2b2b/g |
%s/282828/40403f/g |
%s/383838/6b6a69/g |
%s/585858/807e7c/g |
%s/b8b8b8/aba9a4/g |
%s/d8d8d8/bfbbb2/g |
%s/e8e8e8/ebe2d1/g |
%s/f8f8f8/fff1d4/g |

%s/ab4642/ff4161/g |
%s/dc9656/ff8040/g |
%s/f7ca88/d49034/g |
%s/a1b56c/59ab48/g |
%s/86c1b9/55ab9d/g |
%s/7cafc2/46a4d4/g |
%s/ba8baf/987ad4/g |
%s/a16946/eb75c4/g |

%s/LineNr",        s:gui03, s:gui01, s:cterm03, s:cterm01/LineNr",        s:gui04, s:gui01, s:cterm04, s:cterm01/ |

%s/statusline",    s:gui04, s:gui02, s:cterm04, s:cterm02/statusline",    s:gui09, s:gui01, s:cterm09, s:cterm01/ |

%s/StatusLineNC",  s:gui03, s:gui01, s:cterm03, s:cterm01/StatusLineNC",  s:gui09, s:gui01, s:cterm09, s:cterm01/
```
