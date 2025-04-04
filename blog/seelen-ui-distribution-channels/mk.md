# **UI на Seelen: Методи за инсталација и канали за ажурирање**

## **Опции за инсталација**

### **Microsoft Store (MSIX)**

Преземете ја најновата верзија од продавницата на Мајкрософт. Ова е најбезбедно
 и опција за корисникот, со автоматски ажурирања.

*   Позитивни:
    *   Автоматски ажурирања.
    *   Потврдено и одобрено од Мајкрософт.
    *   Висока безбедност и сигурност.
    *   Лесна верзија од .exe инсталаторот затоа што оваа верзија не
         Вклучува симболи за дебагирање.
*   Конс:
    *   Ажурирањата може да бидат потребни 1-3 работни дена за да бидат одобрени.
    *   Потешко за дебагирање и известување за прашања.

***

### **Вингет (msix)**

Инсталирајте ја најновата верзија користејќи ја следната команда:

```pwsh
winget install --id Seelen.SeelenUI
```

Исти добрите и лошите страни на Мајкрософт продавница со плус на брза инсталација преку
 Командна линија.

***

### \*\*. Exe Installer \*\*

Преземете го инсталаторот Setup.exe од страницата изданија и извршете го.

*   Позитивни:
    *   Побрза инсталација со непосредни ажурирања.
    *   Добива известувања за нови изданија веднаш штом се достапни.
*   Конс:
    *   Не дигитално потпишано, што може да предизвика антивирусни предупредувања.
    *   Помалку лесен од инсталаторот MSIX затоа што оваа верзија вклучува дебагирање
         Симболи.

## **Ажурирајте ги каналите**

> Индепендент на каналот за ажурирање Сите верзии добиваат автоматски ажурирања,
>  Исто така, ако користите нестабилен канал за ажурирање, исто така, ќе добиете ажурирања на
>  Постабилни канали за ажурирање, пример: Ноќни приноси ажурирања од ноќно, но
>  исто така од бета и ослободување

### **Ослободување (стабилно)**

Најсигурен и препорачан канал за сите корисници.

*   Карактеристики:
    *   Темелно тестирани без критични грешки.
    *   Идеално за производство и секојдневна употреба.
    *   Достапно на Microsoft Store, Winget, .msix и .exe.

### **Бета**

Насочени кон корисници кои сакаат да пробаат нови функции пред да бидат официјално објавени.
 Овој канал вклучува бета и кандидати за ослободување.

*   Карактеристики:
    *   Содржи нови функции под тестирање.
    *   Може да има мали грешки.
    *   Почести ажурирања од стабилното издание.
    *   Достапно само како .exe на страницата за изданија.

### **Ноќно**

За напредни корисници и развивачи кои сакаат пристап до најновите промени и
 Експериментални карактеристики.

*   Карактеристики:
    *   Вклучува најнови промени, но не и темелно тестирани.
    *   Може да содржи грешки или недовршени карактеристики.
    *   Ажурирано дневно или со секоја значајна промена на кодот.
    *   Достапно само како .exe на страницата за изданија.

Прочитајте повеќе за на [Селен Уи близу](./nightly.md)

## **Примање ажурирања на setup.exe vs msix**

На MSIX ажурирањата управуваат продавницата на Microsoft, но на Setup.exe тие се
 не, така што ажурирачот е вклучен со апликацијата, ова ќе ви покаже а
 Известување кога е достапно ажурирање.

![Seelen UI update notification on settings window](https://github.com/Seelen-Inc/slu-blog/blob/master/blog/seelen-ui-distribution-channels/image.png?raw=true)

Ако кликнете на известувањето, ќе започне со преземање и инсталирање на
 Ажурирање, по што автоматски ќе ја рестартира апликацијата.
