LCD-Bildschirm
----
*(Seeed Studio Grove – LCD RGB Backlight)*

<img src=https://www.makeyourschool.de/wp-content/uploads/2018/10/62_lcd-bildschirm-1024x1024.jpg width=400px>

Bildquelle: *Wissenschaft im Dialog*

Der LCD Bildschirm dient hautpsächlich zum Anzeigen von Informationen. Er verfügt über zwei Zeilen, auf denen jeweils 16 Zeichen (Buchstaben, Zahlen und Sonderzeichen) dargestellt werden können. Zusätzlich lässt sich die Farbe der Hintergrundbeleuchtung steuern, um einen besonderen Effekt zu erzeugen. Der Bildschirm kann direkt oder mithilfe des Grove Shields an einen Arduino oder Raspberry Pi über die serielle Schnittstelle I2C angeschlossen werden.

Im Folgenden sind sind die grundlegenden Befehle (bisher nur auf englischer Sprache) aufgezählt:


## Usage:

This is an Arudino Library. It include a .h file, a .cpp file and some examples. Through these examples, you can quickly master the use of Grove - LCD RGB Backlight.

The in the following, we will introduce some functions which are used very intuitively. 


### Initialization
Before we use this lcd, we should initialize it. You can use this function:

    lcd.begin(16, 2);

This means that this lcd has 16 columns and 2 rows.


### Change Color of Backlight
One of Grove - LCD RGB Backlight's most important feature is changing the backlight color. It's very simple; just use the folowing function:

    void setRGB(int r, int g, int b);


### Clear Display

You can clear the display by this function:

    void clear();

### Turn on and turn off display

    void noDisplay();			// turn off display
    void display();				// turn on display

### Blink

    void noBlink();
    void blink();

### Cursor

    void noCursor();
    void cursor();

### Blink LED Backlight

    void noBlinkLED();
    void blinkLED();


For more information, please refer to [wiki page](http://wiki.seeedstudio.com/Grove-LCD_RGB_Backlight/).

    
----

Im Rahmen von [*Make Your School*](https://www.makeyourschool.de/) finden an Schulen Hackdays statt. Dabei überlegen sich Schülerinnen und Schüler, wie sie ihre Schule mitgestalten und mit technischen und digitalen Tools noch besser machen können. Unterstützt werden sie dabei von Mentorinnen und Mentoren, die die Veranstaltung begleiten und fachliche Impulse geben. *Make Your School* ist ein Projekt von *Wissenschaft im Dialog*. Die Klaus Tschira Stiftung ist bundesweiter Förderer.

Mit diesen **Bibliotheken und Beispiel-Codes** kann der euch vorliegende Sensor/Aktor getestet werden. Den **Mentorinnen und Mentoren von *Make Your School*** steht es frei, die hier zusammengestellten Codes **nach Bedarf und den individuell gemachten Erfahrungen anzupassen**. Beispiele können einfach im Ordner „examples“ hinzugefügt oder bearbeitet werden. Wir werden eure Beiträge regelmäßig prüfen und das Repository mithilfe eurer Änderungsvorschläge aktualisieren.

Das Repository basiert grundlegend auf den veröffentlichten Informationen und Codes von Seeed Studio. Die deutsche Übersetzung stammt von *Make Your School*, Fehlinterpretationen und Änderungen vorbehalten. Die Informationen dürfen frei genutzt, angepasst und verbreitet werden, solange die Lizenzrechte (siehe License.txt) beachtet werden.


**Weitere Informationen:**

[Repository von Seeed Studio](https://github.com/Seeed-Studio/Grove_LCD_RGB_Backlight)

[Offizielles Wiki von Seeed Studio](http://wiki.seeedstudio.com/Grove-LCD_RGB_Backlight/)

[Materialkoffer von *Make Your School*](https://www.makeyourschool.de/material/lcd-bildschirm/)
