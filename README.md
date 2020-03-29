# VK-chat-spam-script-2
Спамьте, пока не забанят!  ;)


1) Заходим в любой диалог/беседу
2) Вставляем в консоль скрипт
3) Там где i<20 можно поставить любое число, но, вк не позволяет отправлять больше 4к символов. 
   В моем примере выходит примерно 1700+ строк за раз
4) В кавычках пишем любой свой текст
5) Enter в консоли

____________________________________________________
let textVK = document.querySelector('.im_editable.im-chat-input--text._im_text');
let pushBTN = document.querySelector('.im-send-btn.im-chat-input--send.im-send-btn_static._im_send.im-send-btn_send');
for (let i=0; i <20; i++){
textVK.innerHTML += `Это написал бот!<br/><b>`;
}
pushBTN.click();
____________________________________________________
