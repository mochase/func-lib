/i : 不区分大小写.

/s: 单行模式. 影响`.`符的含义, 此时`.`包含了`[\r\n]`

/m: 多行模式,影响`$ ^`符的含义,此时`$ ^`匹配每一行的行首和行尾.

/g: 全局匹配,影响某些api的行为, 
如 `str.replace(reg, '')`会替换所有匹配, 而不是只替换一次.

> 多行模式和单行模式并没有什么对应关系