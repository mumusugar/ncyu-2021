Example 4:

1. 先執行以下指令, 會準備好 ncyu-2021-ex4 資料夾

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex4/scripts/ex4-pre.sh) GITHUB_ACCOUNT
```

2. 切到 ncyu-2021-ex4 資料夾下. 依照投影片描述做修改

3. 交換兩筆 commit: `d695e04`("Example 4: 3") 和 `824d1cd`("Example 4: 2")
   [提示]
   ● 修改前可透過 `git log` 指令確認當前 commit 資訊，已得知後續 `git rebase -i` 後續所需之 commit 編號
   ● 進行 rebase 及 merge 指令時，如遇到 conflict ，使用 `git status` 指令了解 conflict 原因
   ● 修改時，需要按照原有的commit做修改，可用tig指令查看各commit修改部分
   ● 解決 conflict 後須輸入 `git rebase --continue` 或 `git merge --continue` 以完成已下達之 rebase 、 merge 指令

4. 合併 origin/ex4-3 分支, 不要用 fast forward

5. 完成並 commit 後, 在 ncyu-2021-ex4 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex4/scripts/ex4-test.sh) GITHUB_ACCOUNT
```
