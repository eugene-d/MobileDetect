### MobileDetect Yii Extension
> This extension based on This Extension based on [Mobile_Detect class](https://github.com/serbanghita/Mobile-Detect) writed by Serban Ghita and Victor Stanciu

### Install
In app config:
```php
'components'=>array(
    ...

    'mobileDetect' => array(
        'class' => 'ext.MobileDetect.MobileDetect'
    ),
    
    ...
);
```

### Usage
```php
  $detect = Yii::app()->mobileDetect;
  // call methods
  $detect->isMobile();
  $detect->isTablet();
  $detect->isIphone();
  ...
```

### Links
[Class site](http://mobiledetect.net/)
[Class (GitHub)](https://github.com/serbanghita/Mobile-Detect)
[Yii Example](http://iamsalnikov.ru/examples/mobileDetect)
