## 'Контент' tab: 'Кнопка' component: Link with 'www' can not be saved.

**Severity:** Minor

**Precondition:**
1. Prepare a link on the main page of 'A1' portal: 'https://www.a1.by/ru/'

**Steps:** <br>
1. Log in to the System: https://my.pfmlink.com/login;
Login / Password;
2. Go to the 'Главная' page;
3. Click 'Создать новую страницу' button;
4. Click the 'С чистого листа' button;
5. Open 'Контент' tab;
6. Click the 'Кнопка' button;
7. Click the 'Кнопка' component in the editor workspace;
8. Set link from precondition 1 to 'Ссылка' field.
9. Click the 'Сохранить' button;

**Actual result:** <br>
'The given data was invalid.' message appears.
See:<br>
<img src="https://github.com/Irina-Sakharchuk/Syberry_task2_defects/blob/main/screens/bug3.png" width="250"><br>
```
{"message":"The given data was invalid.","errors":[{"button":{"url":["\u041f\u043e\u043b\u0435 url \u0441\u043e\u0434\u0435\u0440\u0436\u0438\u0442 \u043d\u0435\u0434\u0435\u0439\u0441\u0442\u0432\u0438\u0442\u0435\u043b\u044c\u043d\u044b\u0439 URL."]}}]}
```

**Expected Result:** <br>
Correct link (from precondition 1: 'https://www.a1.by/ru/') should be saved.

**Environment:** <br>
Chrome 90.0.4430.212
