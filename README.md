<h1 align="center">My OSS Contributions</h1>

## Git

- [A memory leak in `fetch_and_setup_pack_index()` when verification of the downloaded pack index fails has been plugged. Also an obsolete `unlink()` call on parse failure has been cleaned up.](https://lore.kernel.org/git/cover.1780321770.git.lorenzo.pegorari2002@gmail.com/)
    - `18decad9` (http: fix memory leak in fetch_and_setup_pack_index(), 2026/06/02)
    - `96ee7f16` (http: cleanup function fetch_and_setup_pack_index(), 2026/06/02)
- [Doc update.](https://lore.kernel.org/git/cover.1772502209.git.lorenzo.pegorari2002@gmail.com/)
    - `a56fa1ca` (doc: gitprotocol-pack: normalize italic formatting, 2026/03/03)
    - `b8091b79` (doc: gitprotocol-pack: improve paragraphs structure, 2026/03/03)
    - `267807ea` (doc: gitprotocol-pack: fix pronoun-antecedent agreement, 2026/03/03)
- ["git log --graph --stat" did not count the display width of colored graph part of its own output correctly, which has been corrected.](https://lore.kernel.org/git/cover.1772226209.git.lorenzo.pegorari2002@gmail.com/)
    - `064b869e` (t4052: test for diffstat width when prefix contains ANSI escape codes, 2026/02/27)
    - `1a9df8de` (diff: handle ANSI escape codes in prefix when calculating diffstat width, 2026/02/27)
- [The computation of column width made by "git diff --stat" was confused when pathnames contain non-ASCII characters.](https://lore.kernel.org/git/cover.1768520441.git.lorenzo.pegorari2002@gmail.com/)
    - `04f5d95e` (t4073: add test for diffstat paths length when containing UTF-8 chars, 2026/01/17)
    - `f85b49f3` (diff: improve scaling of filenames in diffstat to handle UTF-8 chars, 2026/01/16)
