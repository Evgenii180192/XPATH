# Xpath
 1. Посмотреть сколько всего элементов в html - документе - `//*`
 2. Посмотреть сколько `<div>` на странице - `//div`
 3. Найти элемент <div class="filter"> - `//div[@class="filter"]`
 4. Найти при помощи метода text() элемента span с текстом SEAT - `//span[text()='SEAT']`
 5. Найти по атрибуту элемент input с атрибутом value="off" - `//input[@value="off"]`
 6. Найти все div в классе которого есть слово filter при помощи метода contains() - `//div[contains(@class,"filter")]`
