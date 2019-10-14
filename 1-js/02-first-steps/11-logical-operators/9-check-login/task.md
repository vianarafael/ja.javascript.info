importance: 3

---

# ログインのチェック

`prompt` でログインを要求するコードを書いてください。

<<<<<<< HEAD:1-js/02-first-steps/10-ifelse/4-check-login/task.md
もし訪問者が `"Admin"` と入力したら、パスワードのための `prompt` を出します。もし入力が空行または `key:Esc` の場合 -- "Canceled" と表示します。別の文字列の場合は -- "I don't know you" と表示します。
=======
If the visitor enters `"Admin"`, then `prompt` for a password, if the input is an empty line or `key:Esc` -- show "Canceled", if it's another string -- then show "I don't know you".
>>>>>>> a0bfa924a17cad8e7fee213904b27dbf57c2dbac:1-js/02-first-steps/11-logical-operators/9-check-login/task.md

パスワードは次に沿ってチェックされます:

<<<<<<< HEAD:1-js/02-first-steps/10-ifelse/4-check-login/task.md
- ”TheMaster" と等しい場合には "Welcome!" と表示します。
- 別の文字列の場合 -- "Wrong password" を表示します。
- 空文字または入力がキャンセルされた場合には "Canceled." と表示します。
=======
- If it equals "TheMaster", then show "Welcome!",
- Another string -- show "Wrong password",
- For an empty string or cancelled input, show "Canceled"
>>>>>>> a0bfa924a17cad8e7fee213904b27dbf57c2dbac:1-js/02-first-steps/11-logical-operators/9-check-login/task.md


<<<<<<< HEAD:1-js/02-first-steps/10-ifelse/4-check-login/task.md
図:
=======
![](ifelse_task.svg)
>>>>>>> a0bfa924a17cad8e7fee213904b27dbf57c2dbac:1-js/02-first-steps/11-logical-operators/9-check-login/task.md

![](ifelse_task.svg)

入れ子の `if` ブロックを使ってください。コードの全体的な読みやすさに気をつけてください。

Hint:  passing an empty input to a prompt returns an empty string `''`. Pressing `key:ESC` during a prompt returns `null`.

[demo]