# form-input-check

フォームから送信する文字列

```
1. 予約文字
,'" ./\=?!:;
","a","b"

2. カタカナ、半角カタカナ
ヲンヰヱヴーヾ・
ｧｰｭｿﾏﾞﾟ

3. 環境依存文字
㌶Ⅲ⑳㏾☎㈱髙﨑

4. マッピングに差がある文字
¢£¬‖−〜―

5. サロゲートペア
𠀋𡈽𡌛𡑮𡢽𠮟𡚴𡸴𣇄𣗄

6. 絵文字
😀🐱🚗

7. EUCのサーバで文字化けする文字
ソ能表

8. javascript
<script>alert('Bug!!!');</script>

9. HTML
<input type="text" value="

10. HTML特殊文字
&lt;&copy;&amp;

```
