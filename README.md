# kamaDatepicker
A jQuery based datepicker for jalali (shamsi) calendar. <a href="http://www.jqueryscript.net/demo/Persian-Jalali-Calendar-Data-Picker-Plugin-With-jQuery-kamaDatepicker/" target="_blank">Demo</a>

## Usage

After adding jQuery to your project, also add the kamadatepicker.js and kamadatepicker.css files to your project.

### HTML:
```html 
<input type="text" id="test-date-id">
```

### JavaScript:
```js 
kamaDatepicker('test-date-id');
```


You can also add custom settings as the second parameter.

### JavaScript:
```js 
kamaDatepicker('test-date-id', { buttonsColor: "red", forceFarsiDigits: true });
```



### Settings

| Description | Default Value | Acceptable Values | Name |
| --- | --- | --- | --- |
| - | "" | string | placeholder |
| If true, single-digit numbers like eight will be displayed with a leading zero (08). | true | true, false | twodigit |
| If true, the calendar will close after selecting a date. | true | true, false | closeAfterSelect |
| You can pass the address of an image or a class of font awesome or glyphy icons as a string to be displayed instead of the "next" phrase in the calendar. | Next | string | nextButtonIcon |
| You can pass the address of an image or a class of font awesome or glyphy icons as a string to be displayed instead of the "previous" phrase in the calendar. | Previous | string | previousButtonIcon |
| You can pass one of the standard color names such as "red" or in the format "#FF0000". | Default | string | buttonsColor |
| If true, regardless of whether Persian numbers are supported in the used font, the calendar uses Persian numbers to display digits. | false | true, false | forceFarsiDigits |
| If true, it distinguishes today's date from the other days. | false | true, false | markToday |
| If true, it distinguishes holidays (currently only Fridays) from the other days. | false | true, false | markHolidays |
| If true, it highlights the selected date from the other days. | false | true, false | highlightSelectedDay |
| If true, the calendar displays the year and month corresponding to the input value after opening, otherwise, it will always display today's date. | false | true, false | sync |
| If true, the "go to today" button is displayed at the bottom of the calendar. | false | true, false | gotoToday |
| The default year of the calendar | "" | int, string (numeric) | defaultYear |

