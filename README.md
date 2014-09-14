pagemasseditor
==============

Массовый редактор страниц. Позволяет редактировать страницы из админ панели.

В нем вы можете самостоятельно настроить поля для редактирования.
Так же есть функция массового применения свойств.
для этого рядом с каждой позицией добавьте тег:
    
    <input type="checkbox" class="checkbox" name="pgch[{PAGEEDIT_FORM_ID}]" />

В завершении формы кнопки

    <button type="submit" class="negative button" name="ractionch" value="delete">{PHP.L.Delete}</button>
    <!-- для удаления страницы -->
	<button type="submit" class="negative button" name="ractionch" value="shop_instock = 0">Нет в наличии</button>
    <!-- для применеия свойств в формате value = "имя_поля = значение" -->
