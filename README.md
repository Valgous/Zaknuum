# Изменение nuum для удобства
![image](https://github.com/user-attachments/assets/a0b081e6-9066-464a-a9e5-fa314cf4fab1)


Для удобного изменения необходимо расширение Stylish.
Скачать можно тут: https://chromewebstore.google.com/detail/stylish-—-настраиваемые-т/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=ru),&pli=1
или набрать в поисковике "Stylish расширение"


Открыть страницу на nuum и открыть расширение.

Открыть редактор (3 вкладка), вписать любое название и вставить код снизу:


.block__messages__item .sticker {
	visibility: none;
  display: none;
}
body {
  background-color: #303030;
}
.header-username__link {
    color: #f35626;
    background-image: -webkit-linear-gradient(92deg, #f35626, #feab3a);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    -webkit-animation: hue 60s infinite linear;
}
@-webkit-keyframes hue {
    from {
      -webkit-filter: hue-rotate(0deg);
    }
    to {
      -webkit-filter: hue-rotate(360deg);
    }
}
.message__body-text {
    padding-top: -5px;
}

![image](https://github.com/user-attachments/assets/eaf3b71f-2099-497a-8b57-a36d31fcbdb0)



Далее нажать на нопку сохранить. Профит!





