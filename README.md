# Important Rules
1. Write styles only in scss files in ```styles/``` folder
2. You should not import scss files in your components as it is already imported in ```App.tsx``` If you have your own separate scss file, you should import it only in ```app.scss```
3. Use the "БЭМ" methology to avoid conflicts in naming your selectors in scss.
4. Make a pull request as soon as you finish your task and do not forget to update Trello
5. Do not download any packages if they have version conflicts.

<br />

# What to do in case of dependencies conflicts?
```bash
npm run reinstall
```

<br />

# How to build the project?

```bash
npm run build
git add -f dist
git commit -m "building"
git subtree push --prefix dist origin gh-pages 
```

In case of merge conflicts in dist:
```bash
git subtree split --prefix dist -b gh-pages
git push -f origin gh-pages:gh-pages
```
<br>

# ТЗ
### Блог:
1. Карла может зайти и выкладывать свои посты в ленте
2. На пост можно кликнуть и будет виден текст который Карла туда напишет (оформление текста она может делать на свое усмотрение, для этого полагаю нужно как то подключить сторонний функционал по типу кастомного редактора текста)
3. Тескт сохраняется и отправляется на бэкенд.
4. Текст можно добавлять, редактировать и удалять.
5. Пост можно добавить изменить или удалить
6. Цвета должны быть похожими на те что я использовал у Дарии в портфолио. Стиль того портфолио можно скопировать.
7. По дизайну ориентируйся больше на корейский стиль в светлых тонах и сделай максимально девчачьим.
8. По тому как будет выглядеть лента и посты все up to you.
9. Комментарии, лайки и тд не нужно. Только тот функционал который я прописал.
10. Очень желательно сначала начать делать сайт под мобилку а только потом в css подстраивать все это под десктоп, потому что скорее всего люди будут смотреть ее сайт с телефонов.
11. Локализацию делать не обязательно потому что посты будут на том языке на котором хочет Карла.
12. Понадобится знание fetch или axios для api запросов на бэк. Плюс еще надо понять как она может делать кастомный текст (где хочет там будет жирный текст или текст другого цвета, размер шрифта и тд), либо придумайте work-around.

Удачи🔥🔥🔥

<hr>

### Портфолио
1. Портфолио для Карлы по ее CV
2. Добавить мотивационные письма, работу и достижения
3. Сделать в виде сторителлинга
4. Добавить отзывы клиентов по ее работе