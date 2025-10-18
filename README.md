Bauteile:
  - 2x Artic P12 Max - PC Lüfter
  - 2x 608Z Kugellager
  - ESP32 Dev Kit
  - SG90 Servo
  - Buck Converter 
  - 12v Netzteil

Zu den PC Lüfter:
Ich hab drauf geachtet welche zu nehmen, die PWM gesteuert sind und auch über PWM ausgeschaltet werden können. Solltest du andere nehmen, achte darauf, dass die das auch haben. 

Code ist in der YAML Datei. Würde den nur als Inspiration nutzen, ESP Home generiert ja auch eigene dinge bei ner neuen Datei.
Was wichtig ist beim Code: Manche PWM Lüfter brauchen ein open_drain. Wenn man den weg lässt, lassen sich die Lüfter nicht richtig steuern.
