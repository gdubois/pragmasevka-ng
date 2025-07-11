# Pragmasevka-NG Font

This was a temporary follow-up to the great work of @shytikov with Pragmasevka that had unfortunately not been updated for over a year.
The original repo has now been recently updated, so there shouldn't be any need for this any more. 

Here is comparison with PragmataPro (black, the image taken from [Wikipedia](https://en.wikipedia.org/wiki/PragmataPro)):

![Comparison with PragmataPro](https://github.com/gdubois/pragmasevka-ng/blob/main/sample.png?raw=true)

Yes, it's not a carbon copy. But metrics are pretty close. 

## The story

Do you love [PragmataPro](https://fsd.it/shop/fonts/pragmatapro/) as we do? You probably do, if you're reading this.

`PragmataPro` is awesome. It's condensed enough, but not too much. Its ``xHeight`` is spot on. Every character seems to be of the best possible shape for readability. There is no better font if you want to make most out of the screen real estate. But there is a catch: although it worth every penny, `PragmataPro` is not free.

There were many attemps to achieve same goals as `PragmataPro` did: condensed with increased `xHeight`. I can name a few:

- [Input](https://input.djr.com/);
- [Monoid](https://larsenwork.com/monoid/);
- [Victor Mono](https://rubjo.github.io/victor-mono/);
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/);

But [Iosevka](https://github.com/be5invis/Iosevka) stands out of the crowd the most. The sole intention from very beginning of this font was to immitate `PragmataPro` as closely as possible. And first public versions proves that. But with time the font matured to a framework that able to provide much more than just a copy of very good font.

Till the day we have `SS08` stylistic set of `Iosevka` that mimics `PragmataPro`. But does it do the best possible job?  

## Improving Iosevka SS08

Investigating public images of text written in `PragmataPro` and having quite limited time and resources @shytikov was able to spot following differences between The Original and `SS08`:

- `xHeight` of `SS08` seems to be smaller;
- The line height of `SS08` seems to be larger;
- `SS08` Regular looks a tiny bit thinner;
- `SS08` Bold looks noticeably thinner;
- `SS08` punctuation marks are consistent with the rest of the font, while PragmataPro has them slightly bolder;
- There are slight differences in programming ligatures used;

Luckly `Iosevka` allows some very sophisticated tweaking, so @shytikov tried his best to improve on "poor man's Pragmata" by fixing these.

## I want one

Head to [Releases](https://github.com/gdubois/pragmasevka-ng/releases) and pick the archive you like: the bare build or [Nerd Fonts](https://www.nerdfonts.com/) enabled one.

You can also build it locally with the following prerequisites
- make
- docker

### Linux
```sh
make images && make font
```

### Windows - WSL
```sh
wsl
make images && make font
```

## Improving it

Let's face it – `PragmataPro` is perfect. And we all should buy it. And I will go it too exactly that day I would get bored from playing with `Iosevka`. And meanwhile if you have spotted something that could be improved, please file an [issue](https://github.com/gdubois/pragmasevka-ng/issues).

## Also worth checking

- [NRK-Mono](https://github.com/N-R-K/NRK-Mono) - All benefits of [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono) with more condensed option;
- [Iosvmata](https://github.com/N-R-K/Iosvmata) - More extended version of Pragmasevka;
