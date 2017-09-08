These are the Vim commands applied to the 'base16-solarized' colour scheme files in order to transmogrify them into the carbonized files.

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


%s/181818/2b2b2b/ |
%s/282828/40403f/ |
%s/383838/6b6a69/ |
%s/585858/807e7c/ |
%s/b8b8b8/aba9a4/ |
%s/d8d8d8/bfbbb2/ |
%s/e8e8e8/ebe2d1/ |
%s/f8f8f8/fff1d4/ |

%s/ab4642/ff4161/ |
%s/dc9656/ff8040/ |
%s/f7ca88/d49034/ |
%s/a1b56c/59ab48/ |
%s/86c1b9/55ab9d/ |
%s/7cafc2/46a4d4/ |
%s/ba8baf/987ad4/ |
%s/a16946/eb75c4/ |

%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui09, s:cterm00, s:cterm09/ |

%s/LineNr",        s:gui03, s:gui01, s:cterm03, s:cterm01/LineNr",        s:gui04, s:gui01, s:cterm04, s:cterm01/ |

%s/statusline",    s:gui04, s:gui02, s:cterm04, s:cterm02/statusline",    s:gui00, s:gui09, s:cterm00, s:cterm09/ |

%s/StatusLineNC",  s:gui03, s:gui01, s:cterm03, s:cterm01/StatusLineNC",  s:gui09, s:gui01, s:cterm09, s:cterm01/ |

%s/WildMenu",      s:gui08, s:gui0A/WildMenu",      s:gui08, s:gui00/
```
