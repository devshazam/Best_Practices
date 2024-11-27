# Язык TSX
	_feature:
		- MAP: использование циклов (пример: map())
			- ⚠️ Нельзя использовать пустые кавычки (<></>) - будет ошибка ключей
				- НО можно не использовать вообще ничего межды вложенными map() - тогда и ключей не надо!
			- Свойство key принимает как числа так и строки
				- При множественной вложенности можно уникализировать key={'w_' + i}
		- Hook: хуки действуют только на часть после return, иначе нужно применять useEffect
		- ⚠️ Контекст исполнения: функции вызываемые событиями типа (onClick) имеют контекст исполнения при создании.
			- 