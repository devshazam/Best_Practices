# Задача BEM => предотвратить конфликт классов без использования модулей

- Стандартное Именование:
    - nav-buttom // через "-" описательное

- B__E--M block__element--modifer
    - nav__nav-buttom--first
        - возможна только одна вложенность = значит, что все потомки в одном родителе не зависимо от вложености
        - чаще всего modifer не используют