# Дубликатор домофонных ключей на Arduino
===============================================================================
# Коды универсальных ключей (в формате DALLAS)

byte newID[8] = {0x01, 0xBE, 0x40, 0x11, 0x5A, 0x36, 0x00, 0xE1}; //– код универсального ключа, для Vizit    

byte newID[8] = {0x01, 0xBE, 0x40, 0x11, 0x5A, 0x56, 0x00, 0xBB}; //- проверен работает Vizit     

byte newID[8] = {0x01, 0xBE, 0x40, 0x11, 0x00, 0x00, 0x00, 0x77}; //- проверен работает Vizit    

byte newID[8] = {0x01, 0xBE, 0x40, 0x11, 0x0A, 0x00, 0x00, 0x1D}; //- проверен работает Визит иногда КЕЙМАНЫ     

byte newID[8] = {0x01, 0xFF, 0xFF, 0xFF, 0xFF, 0xFF, 0xFF, 0x2F}; //- проверен работает метаком, некоторые цифралы.     

byte newID[8] = {0x01, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0x00, 0x9B}; //- проверен Метаком - ещё один.     

byte newID[8] = {0xFF, 0xFF, 0xFF, 0xFF, 0xFF, 0xFF, 0xFF, 0x14}; //???-Открываает 98% Метаком и некоторые Цифрал     

byte newID[8] = {0x01, 0x00, 0x00, 0x00, 0x00, 0x90, 0x19, 0xFF); //???-Отлично работает на старых домофонах     

byte newID[8] = {0x01, 0x6F, 0x2E, 0x88, 0x8A, 0x00, 0x00, 0x4D); //???-Открывать что-то должен     

byte newID[8] = {0x01, 0x53, 0xD4, 0xFE, 0x00, 0x00, 0x7E, 0x88); //???-Cyfral, Metakom     

byte newID[8] = {0x01, 0x53, 0xD4, 0xFE, 0x00, 0x00, 0x00, 0x6F); //???-домофоны Визит (Vizit) - до 99%   

byte newID[8] = {0x01, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x3D); //???-домофоны Cyfral CCD-20 - до 70%     

byte newID[8] = {0x01, 0x00, 0xBE, 0x11, 0xAA, 0x00, 0x00, 0xFB); //???-домофоны Кейман (KEYMAN)     

byte newID[8] = {0x01, 0x76, 0xB8, 0x2E, 0x0F, 0x00, 0x00, 0x5C); //???-домофоны Форвард
