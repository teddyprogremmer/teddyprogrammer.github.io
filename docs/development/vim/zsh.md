1. 安裝 [oh-my-zsh](https://ohmyz.sh/)
2. 啟用 `vim-mode` plugin
    ```shell
    $ vim ~/.zshrc

    plugins=(.. vi-mode)
    ```
    在 `~/.zshrc` 檔案的 `plugins` 中加上 `vi-mode` 重新啟動。
3. 設定調整游標樣式:
   ```shell
   # in .zshrc

   ...
   VI_MODE_SET_CURSOR=true
   ```
