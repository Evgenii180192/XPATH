# XPATH
 1. Посмотреть сколько всего элементов в html - документе - `//*`
 2. Посмотреть сколько `<div>` на странице - `//div`
 3. Найти элемент `<div class="filter">` - `//div[@class="filter"]`
 4. Найти при помощи метода text() элемента span с текстом SEAT - `//span[text()='SEAT']`
 5. Найти по атрибуту элемент input с атрибутом value="off" - `//input[@value="off"]`
 6. Найти все div в классе которого есть слово filter при помощи метода contains() - `//div[contains(@class,"filter")]`
 7. Найти элемент с названием "Запчасти ишины" при помощи функции `starts-with()` - `//span[starts-with(text(),'Запчасти')]`
 8. Найти элемент div c id="__next" - `//div[@id="__next"]`
 9. Найти все элементы div которые не имеют id="__next" = `//div[(not(@id="__next"))]`
10. Найти последний дочерний элемент div, элемента div с class="branding-wrapper" - `//div[@class="branding-wrapper"]/child::div[last()]`
11. Найти элемент `a` соответсвующий двум пораметрам - class="journal-inline__link" и текст начинается со слова "Обзоры" - 
                    `//a[@class="journal-inline__link" and starts-with(text(),'Обзоры')]`
12. Найти все элементы `h4` которые соответствуют одному из двух параметров class="footer__title" или по содержащему тексу - 
                    `//h4[@class="footer__title" or text()="Разделы"]`
