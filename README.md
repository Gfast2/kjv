# kjv [![AUR](https://img.shields.io/badge/AUR-kjv--git-blue.svg)](https://aur.archlinux.org/packages/kjv-git/)

<center>
  <img src='./docs/chinese_kjv.gif' />
</center>

Read the Word of God from your terminal. Here I tweak this fork that can searching and showing a Simpliefied Chinese Version. The chinese bible is mined by my other project [***bible-tsv-generator***](https://github.com/Gfast2/bible-tsv-generator).

The chinese bible version is called **"cns"**

## Usage

    usage: ./kjv [flags] [reference...]

      -l      list books
      -W      no line wrap
      -h      show help

      Reference types:
          <Book>
              Individual book
          <Book>:<Chapter>
              Individual chapter of a book
          <Book>:<Chapter>:<Verse>[,<Verse>]...
              Individual verse(s) of a specific chapter of a book
          <Book>:<Chapter>-<Chapter>
              Range of chapters in a book
          <Book>:<Chapter>:<Verse>-<Verse>
              Range of verses in a book chapter
          <Book>:<Chapter>:<Verse>-<Chapter>:<Verse>
              Range of chapters and verses in a book

          /<Search>
              All verses that match a pattern
          <Book>/<Search>
              All verses in a book that match a pattern
          <Book>:<Chapter>/<Search>
              All verses in a chapter of a book that match a pattern

## Build

kjv can be built by cloning the repository and then running make:

    git clone https://github.com/bontibon/kjv.git
    cd kjv
    make

## License

Public domain
