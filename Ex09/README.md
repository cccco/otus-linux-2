Домашнее задание<br/>
Первые шаги с Ansible<br/>
Подготовить стенд на Vagrant как минимум с одним сервером. На этом сервере используя Ansible необходимо развернуть nginx со следующими условиями:<br/>
- необходимо использовать модуль yum/apt<br/>
- конфигурационные файлы должны быть взяты из шаблона jinja2 с перемененными<br/>
- после установки nginx должен быть в режиме enabled в systemd<br/>
- должен быть использован notify для старта nginx после установки<br/>
- сайт должен слушать на нестандартном порту - 8080, для этого использовать переменные в Ansible<br/>
* Сделать все это с использованием Ansible роли<br/>

Домашнее задание считается принятым, если:<br/>
- предоставлен Vagrantfile и готовый playbook/роль ( инструкция по запуску стенда, если посчитаете необходимым )<br/>
- после запуска стенда nginx доступен на порту 8080<br/>
- при написании playbook/роли соблюдены перечисленные в задании условия<br/>
Критерии оценки: Ставим 5 если создан playbook<br/>
Ставим 6 если написана роль <br/>

==========================================================================================================================<br/>
git clone https://github.com/perhamm/otus-linux  && cd Ex9 <br/>
vagrunt up<br/>
<br/>
Выполнены условия ДЗ , в том числе задания с *<br/>
Переменная с номером порта указывается в запускаемом вагрантом файле playbook.yml<br/>

nginx будет доступен по адресу http://192.168.11.101:8080/  <br/>

