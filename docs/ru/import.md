# Как пользоваться импортом?

backend -> настройки -> данные -> import

## Что есть что на этом экране

* *fields* - список полей, которые есть в нашем файле для импорта (как здесь написано, так поля и называются)
* *additional fields* - дополнительные поля
	* *categories* - категории для товара
	* *images* - картинки для товара

	Здесь *process values as* показывает, как интерпретировать значения в этих полях:
		* *id* - как ID
		* *урл* - как урл
		* *название*
		* *файл* - может быть как абсолютным/относительным путём, так и ссылкой (тогда изображение по ссылке скачивается и сохраняется локально

### Настройки

*Multiple Values Delimiter* - разделитель, который используется в *additional fields* (для того, чтобы указать несколько категорий/картинок)

## Требования к csv-файлу

На данный момент это должен быть стандартный csv, т.о.:

* разделитель полей , (запятая)
* текст заключён в " (двойные кавычки)
* порядок полей не важен