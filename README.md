# Reproduce of PhpStorm Issue WI-78247

Clone

```shell
git clone git@github.com:lyrasoft/eva.git
```

Must run both composer and yarn, that can reproduce issue:

```shell
composer install
yarn install
```

After composer and yarn installed, and wait phpstorm indexing, then try to refactor `src/Hello/HelloWorld.php`, it not works.

Video:

[reproduce-video.webm](https://github.com/user-attachments/assets/9a30cd9d-f611-43fe-b3c2-390c6adcc1a6)
