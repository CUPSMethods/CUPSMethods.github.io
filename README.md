
# Columbia Political Science Methods Workshop Website

Site is maintained by [Georgiy Syunyaev](https://github.com/gerasy1987/)

## Theme

[Hyde](https://github.com/poole/hyde) by **Mark Otto**
- <https://github.com/mdo>
- <https://twitter.com/mdo>

## 3 steps to post

1. Initiate post by running `./initpost.sh [options] <post name> <post date>` from the parent folder on your system. Example: `./initpost.sh -c How to replace strings with sed 2016 10 17` will create file `_posts/2016-10-17-how-to-replace-strings-with-sed.md`, which will then will be automatically transformed into `cupsmethods.github.io/how-to-replace-strings-with-sed/` after you `push` the updates to github.
2. Edit `_posts/2016-10-17-how-to-replace-strings-with-sed.md` content. Initially it will only have
    ```
    ---
    layout: post
    title: How to replace strings with sed
    description:
    tag:
    ---
    ```
3. Add links to the `cupsmethods.github.io/how-to-replace-strings-with-sed/` in `schedule.md` and `index.html`

## License

Open sourced under the [MIT license](LICENSE.md).