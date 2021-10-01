# Libft

42 subject

First Circle

# what should we do?(どんな課題？)

Make Library functions, and let them compile as archive file.
ライブラリ関数を作成し、アーカイブファイルとしてコンパイルします。

# Directory Structure(ファイル構成)

```
libft
├── libft.h
├── README.md
└── srcs
   ├── ft_atoi.c
   ├── ft_bzero.c
   ├── ft_calloc.c
   ├── ft_isalnum.c
   ├── ft_isalpha.c
   ├── ft_isascii.c
   ├── ft_isdigit.c
   ├── ft_isprint.c
   ├── ft_itoa.c
   ├── ft_memccpy.c
   ├── ft_memchr.c
   ├── ft_memcmp.c
   ├── ft_memcpy.c
   ├── ft_memmove.c
   ├── ft_memset.c
   ├── ft_putchar_fd.c
   ├── ft_putendl_fd.c
   ├── ft_putnbr_fd.c
   ├── ft_putstr_fd.c
   ├── ft_split.c
   ├── ft_strchr.c
   ├── ft_strdup.c
   ├── ft_strjoin.c
   ├── ft_strlcat.c
   ├── ft_strlcpy.c
   ├── ft_strlen.c
   ├── ft_strmapi.c
   ├── ft_strncmp.c
   ├── ft_strnstr.c
   ├── ft_strrchr.c
   ├── ft_strtrim.c
   ├── ft_substr.c
   ├── ft_tolower.c
   ├── ft_toupper.c
   └── Makefile
```

# Status(課題の進捗)

🎉DONE!!!🥳🎉

[![hkikuchi's 42Project Score](https://badge42.herokuapp.com/api/project/hkikuchi/Libft)](https://github.com/JaeSeoKim/badge42)


# HOW TO MOVE IT?(ENGLISH)
日本語での使用方法の説明は[こちら](#%E3%81%A9%E3%81%86%E3%82%84%E3%81%A3%E3%81%A6%E5%8B%95%E3%81%8B%E3%81%99%E3%81%8B)



1. Git clone this repository to your rocal environment. (If you already git user and could reach here, then you know this command.)

```
git clone git@github.com:HinataKikuchi/minitalk.git
```

2. JUST DO MAKE.

```
$ cd ./libft
$ make -C srcs
```

3. Archive file(named ```libft.a```) will appear in srcs, when successfully Compiled.

4. If you want to use libft funcs in your dir, examples bellow.

```
$ gcc -I./libft -L./libft/srcs -lft <your_source_name>
```

5. FIN.


# どうやって動かすか？

1. このレポジトリをクローンしてください。

```
git clone git@github.com:HinataKikuchi/minitalk.git
```

2. メイクしてもろて

```
$ cd ./libft
$ make -C srcs
```

3. コンパイルに成功するとアーカイブファイル(```libft.a```って名前のやつ)がsrcs下にできます。

4. もしlibft内の関数を自分のファイルで使いたいときは以下の例のように使ってください。

```
$ gcc -I./libft -L./libft/srcs -lft <your_source_name>
```

5. おーわり！
