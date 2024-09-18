# PyTorch docset

Docset version of the [PyTorch 2.4.1 documentation](https://pytorch.org/docs/2.4/).

I couldn't find an up-to-date docset version of the docs, so I decided to build
them on GitHub myself. This version also fixes an issue where some of the
generated docset files contained colons, making them incompatible with the NTFS
filesystem on Windows.

Compatible with the [Dash](https://kapeli.com/dash) and
[Zeal](https://zealdocs.org/) offline documentation browsers.

To install, download the latest docset from the releases page, unzip, and move
the `PyTorch.docset` directory into your docs browser's docset directory.

In Zeal, you can determine your docsets directory by opening preferences
(`Ctrl+,`) and finding the *Docset storage* section under the *General* tab. By
default, this directory will probably be `$HOME/.local/share/Zeal/Zeal/docsets`
on Linux or `%LOCALAPPDATA%\Zeal\Zeal\docsets` on Windows.
