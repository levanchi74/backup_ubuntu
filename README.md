: 1594011337:0;sudo apt-get install powerline fonts-powerline
: 1594011421:0;sudo apt-get install zsh-theme-powerlevel9k
: 1594011607:0;sudo apt-get install zsh-syntax-highlighting
: 1594011651:0;echo "Hello"
: 1594011900:0;sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/\
install.sh -O -)"
: 1594012020:0;sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
: 1594012108:0;echo "source /usr/share/powerlevel9k/powerlevel9k.zsh-theme" >> ~/.zshrc
: 1594012117:0;echo "source /usr/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ~/.zshrc
: 1594012751:0;nano ~/.zshrc
: 1594013705:0;echo "hell"
: 1594013743:0;sudo nano /etc/hostname
: 1594013828:0;reboot
: 1594017956:0;docker run --help
: 1594036822:0;docker container stop vibrant_hamilton
: 1594046709:0;sudo lshw -C network
: 1594047541:0;sudo netplan apply
: 1594048900:0;ls -l /var/crash
: 1594048946:0;sudo rm /var/crash/*
: 1594049280:0;docker run -d --name clickhouse-server --ulimit nofile=262144:262144 -v /home/chile/clickhouse_database/preprocessed_configs/config.xml:/etc/clickhouse-server/config.xml yandex/clickhouse-server
: 1594049401:0;docker start -d clickhouse-server
: 1594049861:0;docker start -a clickhouse-server
: 1594049928:0;docker container start --detach-keys=first-start
: 1594081548:0;git config --global user.email "levanchi74@gmail.com"
: 1594081571:0;git commit -m "learinng materialized view ..."
: 1594081646:0;git remote add origin https://github.com/levanchi74/ClickHouse.git
: 1594081654:0;git push -u origin master
: 1594088877:0;docker run -it --rm --link clickhouse-server:clickhouse-server yandex/clickhouse-client --host clickhouse-server docker run -it --rm --link clickhouse-server:clickhouse-server yandex/clickhouse-client 
: 1594096186:0;show tales
: 1594096189:0;show tables
: 1594109276:0;git commit -m 'compare 2 stype of MV'
: 1594109379:0;git checkout -b modify_type
: 1594121806:0;git commit -m "added higher order func"
: 1594121833:0;git merge modify_type
: 1594121842:0;git log --online --graph
: 1594121856:0;git logs --oneline --graph
: 1594170367:0;cd dictionaries_lib
: 1594170398:0;cd clickhouse_database
: 1594170411:0;cd preprocessed_configs
: 1594179860:0;git commit -m "aggregate func"
: 1594189997:0;git commit -m "added..."
: 1594190012:0;git commit -m "added .."
: 1594190014:0;git push
: 1594255690:0;df -h
: 1594264776:0;bash Anaconda3-2020.02-Linux-x86_64.sh
: 1594264904:0;conda list env
: 1594265003:0;python -v
: 1594265015:0;python version
: 1594265040:0;conda create --name py37 python=3.7
: 1594265355:0;pip install clickhouse_driver[lz4]
: 1594265424:0;pip install clickhouse-driver[lz4]
: 1594265763:0;from clickhouse_driver import Client
: 1594267678:0;docker stop hungry_boyd
: 1594268029:0;docker container prune clickhouse-server
: 1594268111:0;docker container port 
: 1594268119:0;docker container port clickhouse-server
: 1594268271:0;docker container rm clickhouse-server
: 1594268292:0;docker container ps
: 1594268378:0;client.execute('show databases')
: 1594268482:0;source /home/chile/anaconda3/bin/activate
: 1594559370:0;docker container start --detach-keys=first-start -p clickhouse-server
: 1594559449:0;docker container start --detach-keys=first-start -p clickhouse-server 
: 1594559794:0;py -V
: 1594559812:0;py python-driver.py
: 1594559888:0;conda active py37
: 1594559918:0;python python-driver.py
: 1594566193:0;curl localhost:9000
: 1594566675:0;INSERT INTO counter(when,device, value) values \
    ('2017-01-01 00:00:00', 1,10),\
    ('2017-01-01 00:00:00', 1,10)
: 1594601906:0;py
: 1594618992:0;sudo tar xzf pycharm-professional-2020.1.3.tar.gz -C /opt
: 1594619015:0;cd /opt
: 1594619023:0;cd pycharm-2020.1.3
: 1594619044:0;sh pycharm.sh
: 1594619440:0;pycharm.sh
: 1594619473:0;nano .bashrc
: 1594619690:0;which pycharm.sh
: 1594619708:0;cd /opt/pycharm-2020.1.3/bin/
: 1594619796:0;gedit ~/Desktop/Pycharm.desktop
: 1594620039:0;cd Desktop
: 1594620049:0;gedit Pycharm.desktop
: 1594620123:0;cd /opt/pycharm-2020.1.3/bin
: 1594620135:0;rm -R pycharm-2020.1.3
: 1594620152:0;sudo rm -R pycharm-2020.1.3
: 1594620643:0;git config --global user.name "chile"
: 1594620748:0;git config --global user.email "chi.le@primedata.ai"
: 1594620756:0;git config --list
: 1594621609:0;python env list
: 1594621785:0;pip env graph
: 1594622023:0;pipenv sync --help
: 1594622188:0;cd /home/chile/anaconda3/envs
: 1594622266:0;conda activate py37
: 1594622275:0;conda list --revisions
: 1594622310:0;conda list --revisions 2
: 1594622442:0;conda env remove --name py37
: 1594623414:0;git clone https://github.com/primedata-ai/event-processing.git
: 1594623454:0;pycharm-professional .
: 1594623514:0;pip install -U pipenv
: 1594623747:0;python2 -V
: 1594624000:0;pipenv --python 3.7
: 1594624413:0;pipenv graph
: 1594625249:0;git pull origin 101
: 1594625288:0;git config --list --show-origin
: 1594626177:0;docker-compose -v
: 1594626180:0;docker-compose -version
: 1594626305:0;./docker-compose
: 1594626409:0;sudo ./docker-compose
: 1594626421:0;sudo docker-compose --version
: 1594626501:0;sudo rm /usr/local/bin/docker-compose
: 1594626594:0;pip install docker-compose
: 1594626685:0;cd /usr/local/bin
: 1594626727:0;pip uninstall docker-compose
: 1594627350:0;which docker
: 1594627360:0;cd /usr/bin/
: 1594627988:0;sudo curl -L "https://github.com/docker/compose/releases/download/1.26.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
: 1594628008:0;sudo chmod +x /usr/local/bin/docker-compose
: 1594628017:0;sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
: 1594628245:0;ssh-keygen -t rsa 
: 1594628347:0;nano get_ssh_key.pub
: 1594628497:0;nano examples.desktop
: 1594628675:0;gedit get_ssh_key.pub
: 1594628743:0;git cd ~/Documents
: 1594628763:0;ssh-keygen
: 1594628775:0;cat ~/.ssh/id_rsa.pub
: 1594628822:0;git clone git@github.com:primedata-ai/prime.git
: 1594629091:0;pipenv sync --dev
: 1594629157:0;ping goole.com
: 1594629295:0;docker-compose up .
: 1594629310:0;docker-compose up -f Docker-compose.yml
: 1594629334:0;docker-compose up  Docker-compose.yml
: 1594629342:0;docker-compose --version
: 1594629356:0;docker-compose --help
: 1594630803:0;git branch hello-world
: 1594631890:0;faust -A src.workflows.segments_users.app send input '{"segment":"segment2", "state": "in", "user":"user2", "at":"2020-07-10 00:00:00"}'
: 1594632934:0;pip install --help
: 1594632961:0;pip install -U faust
: 1594636422:0;faust -A hello_world send greetings "Hello Kafka topic"
: 1594693561:0;pipenv lock
: 1594693617:0;pipenv sync
: 1594693657:0;docker container ls 
: 1594696984:0;faust -A hello_world worker -l info -p 6067
: 1594699132:0;echo KAFKA_ADVERTISED_LISTENERS
: 1594699158:0;echo $KAFKA_HOME
: 1594699286:0;$KAFKA_HOME/bin/kafka-console-consumer --topic page_views-page_views-changelog --bootstrap-server localhost:9092 --property print.key=True --from-beginning
: 1594699342:0;echo $KAFKA_BOOTSTRAP_SERVERS=
: 1594699358:0;$KAFKA_BOOTSTRAP_SERVERS/bin/kafka-console-consumer --topic page_views-page_views-changelog --bootstrap-server localhost:9092 --property print.key=True --from-beginning
: 1594699503:0;echo $KAFKA_BOOTSTRAP_SERVERS
: 1594699553:0;faust -A page_views send page_views '{"id": "chi", "user": "barr"}'
: 1594699731:0;faust -A page_views send page_views '{"id": "chi", "use": "barr","test":123}'
: 1594699823:0;faust -A page_views send page_views '{"id": "chi", "user": "barr","test":123}'
: 1594699924:0;faust -A page_views send @count_page_views '{"id": "chi", "user": "barr","test":123}'
: 1594700750:0;git checkout -b 101
: 1594700754:0;git checkout -b 102
: 1594700758:0;git push origin 102
: 1594702219:0;faust -A leader worker -l info --web-port 6066
: 1594702223:0;faust -A leader worker -l info --web-port 6067
: 1594702314:0;faust -A leader worker -l info --web-port 6068
: 1594703614:0;faust -A hello_world.py worker -l info
: 1594703730:0;faust -A hello_world greetings_topic "chile"
: 1594703754:0;faust -A hello_world greetings "chile"
: 1594703875:0;faust -A hello_world worker -l info
: 1594703879:0;faust -A hello_world send greetings "chile"
: 1594704989:0;faust -A page_views send page_views '{"id": "foo", "user": "bar"}'
: 1594706751:0;faust -A page_views send greetings '{"id": "chi", "user": "bar"}'
: 1594706800:0;faust -A page_views send page_views '{"id": "chi", "user": "bar"}'
: 1594707159:0;faust -A page_views worker -l info
: 1594708696:0;faust agnets
: 1594708699:0;faust agents
: 1594708716:0;faust agents --help
: 1594712965:0;python send_to_agent.py
: 1594714761:0;faust -A agent send_to_agent 4 8 --print
: 1594714928:0;faust -A agent send_to_agent worker -l info
: 1594715011:0;faust -A agent send_value 4 8 --print
: 1594715152:0;faust -A examples.agent send_value
: 1594715292:0;faust -A agent worker -l info
: 1594715311:0;faust -A agent send_value
: 1594725084:0;python main.py
: 1594735903:0;python yield_from.py
: 1594796280:0;git fetch master
: 1594798768:0;git checkout hello-world
: 1594801061:0;python coroutine.py
: 1594808509:0;git checkout -b PDMVP-123-test
: 1594811706:0;git checkout -b add_config_segments_users
: 1594815101:0;git add prile/http/common/config_loader.py
: 1594869935:0;pip install nose
: 1594871048:0;python TDD/test/test_caculator.py
: 1594872932:0;nosetests -s TDD/test/test_caculator.py
: 1594879558:0;git checkout PDMVP-123
: 1594880543:0;git clone https://github.com/levanchi74/FlaskApi.git
: 1594880764:0;git lo
: 1594880822:0;git checkout 5daef33e
: 1594882264:0;nosetests TDD/test/test_fraction_calculator.py
: 1594882622:0;nosetests python/TDD/test/test_fraction_calculator.py
: 1594883730:0;pip install coverage
: 1594883785:0;pip freeze > requirements.txt
: 1594883809:0;nosetests python/TDD/test
: 1594883885:0;cd TDD/test
: 1594883905:0;nosetests test_caculator.py
: 1594883947:0;nosetests ./
: 1594883963:0;coverage run ./
: 1594883991:0;coverage run test_caculator.py
: 1594884122:0;nosetests TDD/test/test_caculator.py
: 1594884127:0;nosetests TDD/test
: 1594884139:0;coverage run TDD/test
: 1594884146:0;coverage run TDD/test/test_caculator.py
: 1594884958:0;git clone https://gitlab.com/patkennedy79/flask_recipe_app.git
: 1594884999:0;cd flask_recipe_app/web
: 1594885139:0;docker-compose build
: 1594885191:0;cd web
: 1594885224:0;pyhon create_postgres_dockerfile.py
: 1594885229:0;python create_postgres_dockerfile.py
: 1594889369:0;ps -ef | grep pycharm
: 1594889432:0;sudo kill [200~18167~
: 1594889440:0;sudo kill 18167
: 1594889459:0;man ps
: 1594889484:0;ps -ef
: 1594889512:0;sudo kill 3333
: 1594889969:0;sudo apt-get udpate
: 1594890250:0;sudo systemctl restart NetworkManager.service
: 1594890327:0;sudo nmcli networking off
: 1594890334:0;sudo nmcli networking on
: 1594890345:0;sudo service network-manager restart
: 1594890366:0;ps -rf
: 1594890379:0;ps -a
: 1594953722:0;python data_type.py
: 1594957501:0;python test_main.py
: 1594958437:0;noteboook
: 1594966421:0;git branch 
: 1594971314:0;docker-compose up
: 1594971333:0;docker-compose -f Dockerfile up
: 1594971343:0;docker-compose -f Dockerfile.yml up
: 1594971380:0;export REDIS_SERVER='localhost' 
: 1594971424:0;pipenv run faust -A src.workflows.segments_users.app worker -l info
: 1594971575:0;docker-compose -f Docker-compose.yml up
: 1594971593:0;pipenv run faust -A prile.workflows.segments_users.app.segment_update worker -l info
: 1594975743:0;python multi_inheritance.py
: 1594976255:0;python test
: 1594976258:0;python test.py
: 1594979805:0;python  oop.py
: 1595067859:0;rm get_ssh_key
: 1595067861:0;rm get_ssh_key.pub
: 1595067982:0;sudo snap install pycharm-professional --classic
: 1595068363:0;sudo apt-get install python3-distutils
: 1595068377:0;sudo apt-get install python3-apt
: 1595128107:0;exercism --he
: 1595128120:0;which exercism
: 1595128130:0;man exercism
: 1595128142:0;exercism uninstall
: 1595128149:0;exercism --hel
: 1595128151:0;exercism --help
: 1595128309:0;exit()\
exit
: 1595128470:0;snap find
: 1595128518:0;snap find exer
: 1595128622:0;sudo snap remove exercism
: 1595128642:0;rm exercism
: 1595128651:0;exercism
: 1595129205:0;ls -lra
: 1595129209:0;ls -lrt
: 1595129216:0;ls -l sn
: 1595129260:0;man ls
: 1595129542:0;ls -a
: 1595130665:0;sudo -su
: 1595130667:0;sudo su
: 1595131210:0;cat examples.desktop
: 1595131214:0;cat examples.desktop| less
: 1595131417:0;ls -l | grep sn
: 1595131430:0;ls | grep sn
: 1595131475:0;cd chi
: 1595131525:0;cd MyProjects | ls
: 1595131539:0;cd MyProjects | grep Pri
: 1595131547:0;cd MyProjects 
: 1595131580:0;cd Github
: 1595131583:0;cd MyProjects
: 1595131606:0;cat test.py
: 1595131621:0;cat oop.py
: 1595131625:0;cat oop.py| less
: 1595131643:0;cat oop.py | grep print
: 1595131674:0;touch test.txt
: 1595131696:0;echo "print PRINT test Test" > test.txt
: 1595131713:0;cat test.txt| grep print
: 1595132028:0;cat test
: 1595132042:0;grep Test
: 1595132103:0;ls -l | grep test
: 1595132108:0;ls -l | grep -i test
: 1595132131:0;echo "This is a Test file" > Test.txt
: 1595132137:0;ls -l
: 1595132149:0;ls -la | grep test
: 1595132156:0;man grep
: 1595132317:0;cat test.txt | grep -e test
: 1595132341:0;echo "this is a second line test" >> test.txt
: 1595132345:0;cat test.txt
: 1595132357:0;cat test.txt | grep seco
: 1595209964:0;sudo apt install terminator
: 1595213883:0;[200~docker run -it --rm --link clickhouse-server:clickhouse-server yandex/clickhouse-client --host clickhouse-server~
: 1595254374:0;docker container start --detach-keys=first-start clickhouse-server
: 1595258826:0;pưd
: 1595258937:0;ls -la | grep Down
: 1595258944:0;cd Downloads/ls
: 1595258951:0;host
: 1595258955:0;localshot
: 1595258961:0;hostname
: 1595258965:0;whoamin
: 1595258968:0;whoiam
: 1595343753:0;git clone https://github.com/ClickHouse/ClickHouse.git
: 1595389369:0;ps 
: 1595394471:0;docker container ls'
: 1595396610:0;ll
: 1595430509:0;docker container start --detach-keys=first-start clickhouse-server 
: 1595485825:0;date -u
: 1595516287:0;[200~ docker run -it --rm --link clickhouse-server:clickhouse-server yandex/clickhouse-client --host clickhouse-server~
: 1595571181:0;git clone https://github.com/mymarilyn/clickhouse-driver.git
: 1595576435:0;show
: 1595576573:0;conda list | grep clickhouse
: 1595576647:0;conda create -n clickhouse python=3.6
: 1595576718:0;pip install clickhouse-driver
: 1595576732:0;pyton
: 1595584741:0;conda activate clickhouse
: 1595589058:0;git add clickhouse_driver/segments/migration.py
: 1595589141:0;git commit -m 'added triggers analytis"\

: 1595589177:0;git commit -m 'added triggers analytis gender, location, source'\

: 1595589879:0;git origin
: 1595821252:0;git checkout -b master
: 1595821446:0;git pull origin/master
: 1595821685:0;conda create --name even-processing python=3.7
: 1595821757:0;conda env remove --name even-processing
: 1595821773:0;conda create --name event-processing python=3.7
: 1595822921:0;docker ls
: 1595822955:0;docker container help
: 1595822980:0;docker container stop clickhouse-server
: 1595822995:0;docker container stop goofy_noether
: 1595824817:0;source
: 1595825573:0;which uvicorn
: 1595825692:0;cd .prile
: 1595826285:0;which env
: 1595826316:0;env | grep CONFIG_NAMES
: 1595826508:0;echo $HOME
: 1595826517:0;export | grep HOME
: 1595826676:0;export | less
: 1595826914:0;echo CONFIG_NAMESPACE
: 1595826951:0;export | grep CONFIG_NAMESPACE
: 1595826970:0;which CONFIG_NAMESPACE
: 1595835931:0;which alembic
: 1595836394:0;docker run -it --rm --link clickhouse-server:clickhouse-server yandex/clickhouse-client --host clickhouse-server
: 1595836454:0;docker run help
: 1595836535:0;docker run -it --rm --link clickhouse-server:clickhouse-server yandex/clickhouse-client --host event-processing_server_1
: 1595836948:0;docker run -it --rm --link event-processing_server_1:event-processing_server_1 yandex/clickhouse-client --host clickhouse-server
: 1595836988:0;docker run -it --rm --link event-processing_server_1:event-processing_server_1 yandex/clickhouse-client --host event_processing_server_1
: 1595837382:0;alembic revision -m "create test migreation"
: 1595837407:0;alembic history
: 1595837556:0;pip3 install prile
: 1595837632:0;pip3 install .
: 1595837676:0;alembic history
: 1595837701:0;ls
: 1595837703:0;clear
: 1595837790:0;alembic current
: 1595837805:0;alembic hostory
: 1595837808:0;alembic history
: 1595838302:0;alembic revision -m "create test table"
: 1595838318:0;alembic history
: 1595838467:0;alembic current
: 1595838513:0;alembic upgrade head
: 1595838777:0;clear
: 1595838780:0;alembic -V
: 1595838787:0;alembic --version
: 1595838826:0;alembic history --verbose
: 1595838897:0;alembic history --verbose | less
: 1595838912:0;alembic history --verbose | grep base
: 1595838923:0;alembic history
: 1595839007:0;alembic downgrade -1
: 1595839068:0;alembic downgrade base
: 1595839072:0;clear
: 1595839343:0;alembic history
: 1595839435:0;docker ps 
: 1595839473:0;docker exec -it event-processing_server_1 bash
: 1595839719:0;clear
: 1595839730:0;alembic upgrade head
: 1595839744:0;alembic history
: 1595839957:0;export CONFIG_SOURCE=http://localhost:8500
: 1595839972:0;export CONFIG_NAMESPACE=prile
: 1595839985:0;alembic upgrade head
: 1595840093:0;alembic history
: 1595840104:0;alembic downgrade -1
: 1595840122:0;alembic history
: 1595840666:0;alembic current
: 1595840733:0;alembic history
: 1595840938:0;alembic downgrade 
: 1595840942:0;alembic downgrade head
: 1595840953:0;alembic downgrade -1
: 1595841012:0;alembic history
: 1595841039:0;alembic current
: 1595841097:0;alembic upgrade head
: 1595841191:0;clera
: 1595841200:0;alembic current
: 1595841211:0;alembic history
: 1595841276:0;alembic upgrade head
: 1595841335:0;alembic current
: 1595841377:0;alembic history
: 1595841393:0;alembic upgrade 1
: 1595841399:0;alembic upgrade +1
: 1595841417:0;alembic current
: 1595841423:0;alembic history
: 1595841508:0;alembic upgrade head
: 1595841522:0;alembic current
: 1595841573:0;alembic revision -m "create test table"
: 1595841588:0;alembic current
: 1595841604:0;alembic history
: 1595841623:0;alembic upgrade head
: 1595841654:0;alembic downgrade head
: 1595841662:0;alembic downgrade
: 1595841666:0;alembic downgrade -1
: 1595841679:0;alembic current
: 1595842896:0;alembic history
: 1595842909:0;alembic upgrade head
: 1595843656:0;alembic history
: 1595843665:0;alembic current
: 1595843764:0;alembic upgrade head
: 1595844070:0;alembic downgrade -1
: 1595845206:0;clear
: 1595845239:0;alembic revision -m "create profiles table"
: 1595845410:0;alembic current
: 1595845423:0;alembic upgrade head
: 1595845433:0;alembic history
: 1595845496:0;alembic current
: 1595845626:0;alembic downgrade base
: 1595845830:0;alembic hel[
: 1595845835:0;alembic help
: 1595845847:0;alembic show
: 1595845866:0;alembic init
: 1595845897:0;alembic history
: 1595845908:0;alembic upgrade head
: 1595846088:0;alembic init
: 1595846105:0;uvicorn main:app --port 8888 --reload
: 1595846114:0;alembic upgrade head
: 1595846123:0;alembic upgrade history
: 1595846129:0;alembic history
: 1595846134:0;alembic upgrade history
: 1595846137:0;alembic upgrade head
: 1595846178:0;alembic init
: 1595846320:0;alembic init alembic
: 1595846757:0;clear
: 1595846860:0;alembic revision -m "create profiles table"
: 1595846933:0;alembic history
: 1595846937:0;alembic current
: 1595847746:0;uvicorn main:app --port 8888 --reload
: 1595847752:0;clear
: 1595847763:0;alembic current
: 1595847893:0;alembic history
: 1595848003:0;docker ps
: 1595848026:0;docker help
: 1595848078:0;docker stop help
: 1595848081:0;docker stop -help
: 1595848084:0;docker stop -a
: 1595848087:0;docker stop
: 1595848094:0;docker stop --help
: 1595848157:0;docker ps -aq
: 1595848166:0;docker ps --help
: 1595848184:0;docker stop $(docker ps -aq)
: 1595848218:0;history | grep docker-compose
: 1595848234:0;docker-compose up -d
: 1595848242:0;docker ps
: 1595848320:0;uvicorn main:app --port 8888 --reload
: 1595848330:0;export CONFIG_NAMESPACE=prile
: 1595848348:0;export CONFIG_SOURCE=http://localhost:8500
: 1595848354:0;uvicorn main:app --port 8888 --reload
: 1595848368:0;alembic
: 1595848372:0;alembic history
: 1595848376:0;alembic current
: 1595848407:0;export CONFIG_NAMESPACE=prile
: 1595848415:0;export CONFIG_SOURCE=http://localhost:8500
: 1595848418:0;alembic current
: 1595848709:0;alembic init 
: 1595848715:0;alembic init .
: 1595848725:0;ls
: 1595848727:0;clear
: 1595848755:0;alembic init alembic
: 1595848892:0;alembic history
: 1595848897:0;alembic current
: 1595848948:0;pip3 install .
: 1595848987:0;alembic current
: 1595849017:0;alembic history
: 1595849035:0;docker --help
: 1595849060:0;docker ps
: 1595849076:0;docker exec -it event-processing_server_1
: 1595849084:0;docker exec -it event-processing_server_1 bash
: 1595849389:0;alembic history
: 1595849403:0;alembic revision -m "create profiles table"
: 1595849540:0;alembic upgrade head
: 1595849723:0;docker ps
: 1595849758:0;docker exec -it event-processing_db_1
: 1595849890:0;docker exec -it event-processing_db_1 bash
: 1595850632:0;alembic current
: 1595850656:0;history | grep CONFIG_
: 1595850664:0;export CONFIG_NAMESPACE=prile
: 1595850681:0;echo $CONFIG_NAMESPACE
: 1595850703:0;alembic current
: 1595850832:0;alembic history
: 1595850850:0;alembic upgrade head
: 1595851636:0;alembic history
: 1595851655:0;alembic downgrade head
: 1595851662:0;alembic downgrade -1
: 1595851808:0;alembic revision -m "create segments table"
: 1595851845:0;alembic revision -m "create segment agg table"
: 1595851930:0;alembic revision -m "create segment agg gender mv"
: 1595851943:0;alembic revision -m "create segment agg location mv"
: 1595851951:0;alembic revision -m "create segment agg source mv"
: 1595852102:0;alembic revision -m "create segment last point agg table"
: 1595852120:0;alembic revision -m "create segment last point mv"
: 1595852683:0;alembic history
: 1595852692:0;alembic upgrade head
: 1595852722:0;clear
: 1595903039:0;docker ps 
: 1595903071:0;	docker-compose up -d
: 1595903077:0;docker ps
: 1595903087:0;uvicorn main:app --port 8888 --reload
: 1595903134:0;export CONFIG_NAMESPACE=prile
: 1595903143:0;export CONFIG_SOURCE=http://localhost:8500
: 1595903146:0;uvicorn main:app --port 8888 --reload
: 1595903175:0;docker ps
: 1595903205:0;docker exec -it event-processing_server_1 bash
: 1595903237:0;alembic history
: 1595909154:0;pwd
: 1595909154:0;lcear
: 1595909156:0;clear
: 1595910131:0;uvicorn main:app --port 8888 --reload
: 1595918867:0;ls
: 1595918870:0;python
: 1595918876:0;python dip.py
: 1595919716:0;uvicorn main:app --port 8888 --reload
: 1595919730:0;export CONFIG_SOURCE=http://localhost:8500
: 1595919739:0;export CONFIG_NAMESPACE=prile
: 1595919742:0;uvicorn main:app --port 8888 --reload
: 1595919753:0;docker ps
: 1595919768:0;docker exec -it event-processing_server_1 bash
: 1595922382:0;python -V
: 1595922712:0;conda activate event-processing
: 1595922719:0;python -V
: 1595922734:0;conda activate base
: 1595922740:0;python3 -V
: 1595931407:0;clear
: 1595931410:0;uvicorn main:app --port 8888 --reload
: 1595947433:0;export CONFIG_NAMESPACE=prile
: 1595947440:0;export CONFIG_SOURCE=http://localhost:8500
: 1595947443:0;uvicorn main:app --port 8888 --reload
: 1595947527:0;docker ps
: 1595947537:0;	docker-compose up -d
: 1595947552:0;uvicorn main:app --port 8888 --reload
: 1595947564:0;docker exec -it event-processing_server_1 bash
: 1595947868:0;uvicorn main:app --port 8888 --reload
: 1595947949:0;docker ps
: 1595948120:0;uvicorn main:app --port 8888 --reload
: 1595948220:0;docker ps --help
: 1595948228:0;docker ps -aq
: 1595948237:0;$(docker ps -aq)
: 1595948241:0;(docker ps -aq)
: 1595948253:0;docker --help
: 1595948257:0;docker stop --help
: 1595948278:0;docker stop (docker ps -aq)
: 1595948284:0;docker stop $(docker ps -aq)
: 1595948292:0;docker ps
: 1595948301:0;	docker-compose up -d
: 1595948333:0;uvicorn main:app --port 8888 --reload
: 1595949447:0;docker exec -it event-processing_server_1 bash
: 1595955913:0;sudo snap install tusk
: 1595955991:0;tusk
: 1595989269:0;export CONFIG_SOURCE=http://localhost:8500
: 1595989273:0;export CONFIG_NAMESPACE=prile
: 1595989280:0;uvicorn main:app --port 8888 --reload
: 1595989293:0;docker ps
: 1595989304:0;	docker-compose up -d
: 1595989311:0;uvicorn main:app --port 8888 --reload
: 1595989327:0;docker exec -it event-processing_server_1 bash
: 1596008468:0;uvicorn main:app --port 8888 --reload --debug
: 1596008930:0;clear
: 1596008933:0;docker ps
: 1596008940:0;git status
: 1596009095:0;git add .
: 1596009097:0;git status
: 1596009282:0;git commit -m 'segment metric report api'
: 1596009342:0;git checkout -b pydantic
: 1596010196:0;git checkout -b time_range
: 1596012453:0;git clone git@github.com:xzkostyan/clickhouse-sqlalchemy.git
: 1596015792:0;uvicorn main:app --port 8888 --reload --debug
: 1596019538:0;env
: 1596023453:0;clear
: 1596026432:0;git status
: 1596026541:0;git commit -m 'added query by range time to api segment metric report'
: 1596026559:0;git checkout master
: 1596026578:0;git status
: 1596026600:0;git add .
: 1596026602:0;git status
: 1596026608:0;git commit -m 'added query by range time to api segment metric report'
: 1596026639:0;git checkout master
: 1596026649:0;git status
: 1596026667:0;git merge time_range
: 1596026671:0;git status
: 1596027523:0;docker ps
: 1596027553:0;docker exec -it event-processing_server_1 bash
: 1596076784:0;pwd
: 1596076785:0;clear
: 1596076786:0;ls
: 1596076788:0;clear
: 1596077044:0;git status
: 1596077288:0;	docker-compose up -d
: 1596077346:0;docker ps
: 1596077391:0;docker exec -it event-processing_server_1 bash
: 1596094272:0;git pull master
: 1596094279:0;git pull origin master
: 1596098219:0;git show origin master
: 1596098231:0;git show origin
: 1596098258:0;git 
: 1596098261:0;clear
: 1596098268:0;git status
: 1596098501:0;git 
: 1596098505:0;fix conflics
: 1596098576:0;git status
: 1596098581:0;git add .
: 1596098583:0;git status
: 1596098628:0;git commit -m "merge with origin/master"
: 1596098630:0;git status
: 1596099674:0;git pull origin master
: 1596101815:0;pip3 install -r --help
: 1596101823:0;pip3 --help
: 1596101985:0;pip3 install -r requirements.txt
: 1596102436:0;lscpu
: 1596104913:0;conda env list
: 1596116138:0;pwd
: 1596116464:0;git --version
: 1596116472:0;clear
: 1596116484:0;git init
: 1596116505:0;ls
: 1596116507:0;ls -la
: 1596116583:0;touch file1.txt
: 1596116600:0;echo "tho" > file1.txt
: 1596116602:0;cat file1
: 1596116607:0;cat file1.txt
: 1596116627:0;git status
: 1596116752:0;git add file1.txt
: 1596116760:0;git status
: 1596116905:0;git commit -m 'added a line for file1.txt'
: 1596116926:0;git log
: 1596116958:0;git status
: 1596116996:0;echo "chi" >> file1.txt
: 1596116999:0;cat file1.txt
: 1596117004:0;git status
: 1596117043:0;git commit -m "added line 2 to file1.txt"
: 1596117072:0;git add file1.txt
: 1596117076:0;git status
: 1596117134:0;touch file2.txt
: 1596117148:0;echo "tho yeu chi" > file2.txt
: 1596117154:0;git status
: 1596117194:0;git commit -m "edited file1"
: 1596117195:0;git status
: 1596117223:0;git log
: 1596117267:0;git add file2.txt
: 1596117273:0;git status
: 1596117283:0;git commit -m "added file2"
: 1596117288:0;git status
: 1596117297:0;git log
: 1596117307:0;pycharm
: 1596117312:0;pycharm-professional
: 1596117484:0;git branch
: 1596117503:0;git branch login
: 1596117509:0;git branch
: 1596117526:0;git checkout login
: 1596117618:0;git git status
: 1596117621:0;git status
: 1596117711:0;git add file1.txt
: 1596117714:0;git status
: 1596117724:0;git commit -m 'added login function'
: 1596117782:0;git status
: 1596117796:0;git add validation_info.txt
: 1596117798:0;git status
: 1596117814:0;git commit -m 'added validation'
: 1596117817:0;git status
: 1596117893:0;git checkout master
: 1596117918:0;git checkout login
: 1596117957:0;git checkout master
: 1596117964:0;git merge login
: 1596118758:0;git log --oneline --graph
: 1596120165:0;git fetch origin master
: 1596162105:0;	docker-compose up -d
: 1596162115:0;docker exec -it event-processing_server_1 bash
: 1596164854:0;git pull origin master
: 1596187144:0;docker exec -it event-processing_server_1 bash
: 1596188502:0;	docker-compose up -d
: 1596188518:0;docker exec -it event-processing_server_1 bash
: 1596248433:0;	docker-compose up -d
: 1596248443:0;docker exec -it event-processing_server_1 bash
: 1596272369:0;git status
: 1596272438:0;git checkout -b update_metric_mv
: 1596272448:0;git status
: 1596352215:0;sudo apt-get update
: 1596352235:0;sudo apt-get upgrade
: 1596371679:0;git status
: 1596371849:0;docker ps
: 1596371858:0;	docker-compose up -d
: 1596371873:0;docker exec -it event-processing_server_1 bash
: 1596372367:0;git status
: 1596372399:0;git add prile/migration/.
: 1596372401:0;git status
: 1596373057:0;git commit -m '[Segment Analytics] edited mv when profile update'
: 1596419039:0;	docker-compose up -d
: 1596419050:0;docker exec -it event-processing_server_1 bash
: 1596427740:0;export CONFIG_NAMESPACE=prile
: 1596435082:0;alias
: 1596435148:0;quit
: 1596435152:0;eixt
: 1596435156:0;exit
: 1596443974:0;git status
: 1596443986:0;git status | grep console
: 1596443992:0;git status | less
: 1596444492:0;export CONFIG_SOURCE=http://localhost:8500
: 1596444580:0;history
: 1596444611:0;uvicorn main:app --port 8888 --reload --debug
: 1596444623:0;export CONFIG_NAMESPACE=prile 
: 1596444628:0;export CONFIG_SOURCE=http://localhost:8500
: 1596444640:0;uvicorn main:app --port 8888 --reload --debug
: 1596460367:0;clear
: 1596460494:0;docker exec -it event-processing_server_1 bash
: 1596506544:0;docker ps
: 1596589505:0;docker-compose up -d
: 1596589528:0;docker exec -it event-processing_server_1 bash
: 1596616814:0;docker ps
: 1596641534:0;date
: 1596641550:0;now
: 1596641554:0;now()\
date
: 1596641556:0;date
: 1596641563:0;man date
: 1596641595:0;timedatectl | grep "time zone"
: 1596641607:0;timedatectl | grep "Time zone"
: 1596643022:0;timedatectl list-timezones
: 1596643346:0;timedatectl | grep 'Time zone'
: 1596643355:0;timedatectl | grep 'urc'
: 1596643358:0;timedatectl | grep 'utc'
: 1596643378:0;man timedatectl
: 1596677881:0;docker ps
: 1596677920:0;docker-compose up -d
: 1596677933:0;docker ps
: 1596677977:0;docker exec -it event-processing_server_1 bash
: 1596683025:0;git clone git@github.com:primedata-ai/event-processing.git
: 1596683033:0;ls
: 1596683065:0;git branch
: 1596683912:0;git checkout -b develop
: 1596685536:0;git status
: 1596685555:0;git add .
: 1596685558:0;git status
: 1596685793:0;git commit -m '[MVP-177] created generator tepmlate for materialize view'
: 1596685902:0;git branch -m MVP-177
: 1596685905:0;git status
: 1596685922:0;git checkout master
: 1596685933:0;git checkout MVP-177
: 1596685947:0;git push origin MVP-177
: 1596687767:0;git checkout master
: 1596687772:0;git pull origin master
: 1596687865:0;git checkout MVP-177
: 1596688011:0;git checkout master
: 1596688066:0;git checkout MVP-77
: 1596688071:0;git checkout MVP-177
: 1596689657:0;git merge master
: 1596690139:0;git checkout master
: 1596690152:0;git status
: 1596690180:0;git commit -m 'Not merged'
: 1596690248:0;git add .
: 1596690249:0;git status
: 1596690257:0;git commit -m 'not merged'
: 1596690261:0;git checkout master
: 1596690297:0;git branch -d MVP-177
: 1596690323:0;git branch -D MVP-177
: 1596690345:0;git push origin --delelte MVP-177
: 1596690354:0;git push origin --delete MVP-177
: 1596690417:0;git checkout -b MVP-177
: 1596704627:0;git status
: 1596705938:0;git add .
: 1596705940:0;git status
: 1596705993:0;git commit -m '[MVP-177] Created python materialized view template'
: 1596706000:0;git push origin MVP-177
: 1596710092:0;timedatectl list-timezones
: 1596710106:0;timedatectl list-timezones | grep [200~Asia/Yekaterinburg
: 1596710118:0;timedatectl list-timezones | grep 'Asia/Yekaterinburg'
: 1596710218:0;timedatectl
: 1596710230:0;man timedatectl 
: 1596710355:0;cat /etc/timezone
: 1596710741:0;calendar
: 1596710744:0;date
: 1596710964:0;man calendar
: 1596711063:0;man calendar| grep month
: 1596711082:0;man calenda
: 1596711083:0;man calendar
: 1596711148:0;cal(2)
: 1596711151:0;cal(2020)
: 1596711164:0;cal 2020
: 1596711171:0;cal 2020 9
: 1596711174:0;cal 2020 1
: 1596711181:0;cal 9/2020
: 1596711189:0;date
: 1596711192:0;cal
: 1596711195:0;cal 2019
: 1596720549:0;docker exec -it event-processing_server_1 bash
: 1596723804:0;alembic history
: 1596723813:0;alembic current
: 1596723829:0;docker ps
: 1596723839:0;export CONFIG_SOURCE=http://localhost:8500
: 1596723843:0;export CONFIG_NAMESPACE=prile 
: 1596723852:0;uvicorn main:app --port 8888 --reload --debug
: 1596723860:0;ls
: 1596723978:0;conda env list
: 1596724119:0;conda activate event-processing
: 1596724129:0;conda activate base
: 1596724131:0;clear
: 1596724439:0;pip3 -V
: 1596724501:0;ls
: 1596724504:0;clear
: 1596724600:0;pip3 install .
: 1596724682:0;conda list
: 1596724716:0;conda list | grep uvicorn
: 1596725244:0;pip3 install .
: 1596725270:0;git status
: 1596725602:0;conda env list
: 1596725686:0;pip3 install .
: 1596725745:0;conda env list
: 1596725823:0;conda env remove --name /home/chile/anaconda3/envs/event-processing/.py37
: 1596725844:0;conda env remove --name event-processing
: 1596725852:0;conda env list
: 1596725933:0;pip3 install -r requirements.txt
: 1596766049:0;conda list | grep uvicorn
: 1596766060:0;uvicorn main:app --port 8888 --reload --debug
: 1596766095:0;alembic histoty
: 1596766100:0;alembic history
: 1596766113:0;pip3 install .
: 1596766124:0;conda env list
: 1596766198:0;uvicorn main:app --port 8888 --reload
: 1596766600:0;docker-compose up -d
: 1596766622:0;uvicorn main:app --port 8888 --reload
: 1596766659:0;export CONFIG_NAMESPACE=prile 
: 1596766675:0;export CONFIG_SOURCE=http://localhost:8500
: 1596766680:0;uvicorn main:app --port 8888 --reload
: 1596767318:0;git pull origin master
: 1596767375:0;uvicorn main:app --port 8888 --reload
: 1596767711:0;alembic
: 1596767716:0;alembic -current
: 1596767778:0;alembic current
: 1596768039:0;uvicorn main:app --port 8888 --reload
: 1596769406:0;clear
: 1596769663:0;alembic history
: 1596769670:0;alembic current
: 1596770357:0;alembic history
: 1596772710:0;docker exec -it event-processing_server_1 bash
: 1596808515:0;git status
: 1596808517:0;git add .
: 1596808519:0;git status
: 1596808526:0;ls
: 1596808539:0;git add .
: 1596808546:0;cd ..
: 1596808547:0;ls
: 1596808551:0;git status
: 1596808553:0;git add .
: 1596808555:0;git status
: 1596808626:0;git commit -m 'testing for mv generator'
: 1596808672:0;git checkout -b try_replacing_mt
: 1596808725:0;git checkout master
: 1596808753:0;git status
: 1596808764:0;git stauts
: 1596808767:0;git status
: 1596808798:0;git checkout try_replacing_mt
: 1596808808:0;git status
: 1596808830:0;git commit -am 'test branch certain'
: 1596808833:0;git status
: 1596808840:0;git checkout master
: 1596808851:0;git checkout try_replacing_mt
: 1596809280:0;create database c2
: 1596812516:0;docker ps
: 1596812520:0;ps
: 1596812650:0;docker ps
: 1596812660:0;docker-compose up -d
: 1596812709:0;docker ps
: 1596812711:0;clera
: 1596812712:0;clear
: 1596812743:0;docker exec -it event-processing_server_1 bash
: 1596813263:0;git status
: 1596813272:0;git add .
: 1596813275:0;git status
: 1596813339:0;git commit -m 'khong su dung ReplacingMergeTree vs argMax vi size table giam khong dang ke'
: 1596813344:0;git checkout master
: 1596813375:0;git checkout try_replacing_mt
: 1596813384:0;git checkout master
: 1596813503:0;git checkout -b refactor-agg_merge_tree
: 1596854388:0;docker-compose up -d
: 1596854416:0;docker exec -it event-processing_server_1 bash
: 1597019036:0;git checkout master
: 1597019042:0;git pull origin master
: 1597019476:0;export CONFIG_SOURCE=http://localhost:8500
: 1597019482:0;export CONFIG_NAMESPACE=prile 
: 1597019487:0;uvicorn main:app --port 8888 --reload
: 1597019506:0;docker-compose up -d
: 1597019517:0;export CONFIG_NAMESPACE=prile 
: 1597019522:0;export CONFIG_SOURCE=http://localhost:8500
: 1597019527:0;uvicorn main:app --port 8888 --reload
: 1597019535:0;alembic history
: 1597019541:0;alembic current
: 1597020347:0;git pull
: 1597020381:0;git branch origin MVP-154
: 1597020399:0;git checkout origin/MVP-154
: 1597020476:0;git status
: 1597020479:0;git diff
: 1597020509:0;git checkout origin/MVP-154
: 1597021872:0;git checkout master
: 1597021882:0;git status
: 1597021888:0;git checkout refactor-agg_merge_tree
: 1597021890:0;git status
: 1597021924:0;git add event-processing-db/test_case_for_generator_mv.sql
: 1597021937:0;git commit -m 'can not refacotr'
: 1597021947:0;git checkout master
: 1597021950:0;git status
: 1597022012:0;git checkout update_generator_mv
: 1597022021:0;git checkout -b update_generator_mv
: 1597022328:0;docker exec -it event-processing_server_1 bash
: 1597033788:0;clear
: 1597033797:0;git status
: 1597033810:0;git checkout master
: 1597033839:0;git pull origin master
: 1597033972:0;git checkout -b segment_agg_final_v
: 1597035968:0;git status
: 1597035973:0;git add .
: 1597036083:0;git commit -m 'added segments_final and created view for select'
: 1597036107:0;git push origin segment_agg_final_v
: 1597038870:0;git checkout master
: 1597038876:0;git checkout update_generator_mv
: 1597038878:0;git status
: 1597038881:0;git add .
: 1597038908:0;git commit -m 'added segments final and update mv, create view'
: 1597038911:0;git checkout master
: 1597038915:0;git merge update_generator_mv
: 1597038941:0;git status
: 1597042113:0;git checkout master
: 1597042156:0;echo $CONFIG_SOURCE
: 1597042184:0;export
: 1597042223:0;export -p
: 1597042236:0;clear
: 1597042241:0;export
: 1597042532:0;cd
: 1597042542:0;ls
: 1597042543:0;ls -la
: 1597042566:0;ls -la zpro
: 1597042575:0;ls -la | 'zprofile'
: 1597042665:0;pwd
: 1597042730:0;cd /etc/profile.d
: 1597042731:0;ls
: 1597042811:0;touch event_processing_env.sh
: 1597042819:0;sudo touch event_processing_env.sh
: 1597042821:0;ls
: 1597042840:0;sudo nano event_processing_env.sh
: 1597042917:0;ls -la
: 1597042921:0;cat event_processing_env.sh
: 1597042931:0;clear
: 1597042936:0;echo $prile
: 1597042971:0;ls
: 1597042979:0;cat apps-bin-path.sh
: 1597043022:0;ls
: 1597043024:0;cd ..
: 1597043025:0;ls
: 1597043034:0;cat profile
: 1597043068:0;cd profile.d
: 1597043068:0;ls
: 1597043072:0;cat bash_completion.sh
: 1597043104:0;ls
: 1597043111:0;sudo rm event_processing_env.sh
: 1597043112:0;ls
: 1597043131:0;uvicorn main:app --port 8888 --reload
: 1597043143:0;export
: 1597043150:0;export CONFIG_SOURCE=http://localhost:8500
: 1597043156:0;export CONFIG_NAMESPACE=prile 
: 1597043163:0;uvicorn main:app --port 8888 --reload
: 1597043200:0;pip3 install -r requirements.txt
: 1597043472:0;git pull origin master
: 1597046981:0;git checkout -b bugfix/MVP-test
: 1597047179:0;git status
: 1597047183:0;git add .
: 1597047185:0;git status
: 1597047189:0;git commit -m 'test'
: 1597047277:0;git branch --hel[
: 1597047279:0;git branch --help
: 1597047297:0;git branch -d bugfix/MVP-test
: 1597047313:0;git branch -Dbugfix/MVP-test
: 1597047317:0;git branch -D bugfix/MVP-test
: 1597047323:0;git checkout master
: 1597047327:0;git branch -D bugfix/MVP-test
: 1597047386:0;docker ps
: 1597047403:0;pip3 install -r requirements.txt
: 1597047413:0;git pull origin master
: 1597047435:0;pip3 install -r requirements.txt
: 1597047562:0;git pull origin master
: 1597047605:0;git log
: 1597049527:0;conda env list
: 1597049535:0;conda list
: 1597049792:0;ls
: 1597049797:0;ls -la
: 1597049862:0;rm -R .prile
: 1597049864:0;ls
: 1597049865:0;ls -la
: 1597049902:0;git status
: 1597050002:0;env
: 1597050006:0;env list
: 1597050086:0;pip3 install .
: 1597050141:0;pip3 install -r requirements.txt
: 1597050246:0;conda env list
: 1597050249:0;conda list
: 1597050269:0;conda list | 'uvicorn'
: 1597050286:0;conda list | grep 'uvicorn'
: 1597050330:0;conda list | grep 'aredis'
: 1597051592:0;pip3 -V
: 1597051632:0;pip3 install --help
: 1597051739:0;git pull origin master
: 1597052014:0;sudo pip3 install -r requirements.txt
: 1597052063:0;1
: 1597052120:0;pip3 install .
: 1597052130:0;export CONFIG_NAMESPACE=prile 
: 1597052134:0;export CONFIG_SOURCE=http://localhost:8500
: 1597052140:0;uvicorn main:app --port 8888 --reload
: 1597052162:0;docker ps
: 1597052187:0;sudo pip3 install -r requirements.txt
: 1597052321:0;ls -la
: 1597052331:0;rm -R .prile
: 1597052332:0;ls
: 1597052472:0;python -V
: 1597052485:0;python3 -V
: 1597052489:0;which python
: 1597052750:0;conda env list
: 1597052894:0;rm -R .prile
: 1597052895:0;ls
: 1597052937:0;conda env list
: 1597053042:0;conda activate base
: 1597053046:0;conda env list
: 1597053056:0;ls
: 1597053065:0;python3 -V
: 1597053071:0;pip3 -V
: 1597053079:0;pip3 install -r requirements.txt
: 1597053189:0;conda env list
: 1597053232:0;pip3.7 -V
: 1597053238:0;pip3 -V
: 1597053247:0;python -V
: 1597053253:0;python3.7 -V
: 1597053283:0;pip -V
: 1597053303:0;pip install -U setuptools
: 1597053434:0;sudo pip3.7 install -U setuptools
: 1597053446:0;sudo pip3.7 install -r requirements.txt
: 1597053455:0;sudo pip3 install -r requirements.txt
: 1597053518:0;sudo pip3 -V
: 1597053531:0;sudo -H pip3 -V
: 1597053675:0;pip3 install .
: 1597053692:0;pip3 -V
: 1597053702:0;sudo pip3 -V
: 1597053989:0;conda env list
: 1597054702:0;source env/bin/activate
: 1597054704:0;cd
: 1597054719:0;source env/bin/activate
: 1597054726:0;pwd
: 1597054728:0;clear
: 1597054748:0;ls -la | grep source
: 1597054750:0;ls
: 1597054753:0;ls -la
: 1597054854:0;source env/bin/activate
: 1597054871:0;which python
: 1597055188:0;rm -R .prile
: 1597055234:0;pip -V
: 1597055264:0;rm -R .prile
: 1597055265:0;ls
: 1597055547:0;pwd
: 1597055563:0;$(pwd)
: 1597055569:0;echo $(pwd)
: 1597055602:0;source /home/chile/PycharmProjects/Github/PrimeData/event-processing/.prile/bin/activate
: 1597055620:0;pip3 -V
: 1597055629:0;pip3 install -r requirements.txt
: 1597055664:0;conda env list
: 1597055686:0;.prile/bin/activate
: 1597055692:0;sudo .prile/bin/activate
: 1597055709:0;sudo ./.prile/bin/activate
: 1597055718:0;sudo .prile/bin/activate
: 1597055752:0;python3 -V
: 1597055771:0;pip3 -V
: 1597055780:0;pip3 install  .
: 1597055870:0;source .prile/bin/activate
: 1597055876:0;conda activate
: 1597055890:0;conda env list
: 1597055919:0;conda activate base
: 1597055924:0;pip3 -V
: 1597055939:0;source .prile/bin/activate
: 1597055970:0;pip3 install -r requirements.txt
: 1597055980:0;sudo pip3 -V
: 1597056299:0;pip3 install -r requirements.txt
: 1597056349:0;conda env list
: 1597056352:0;conda list
: 1597056539:0;docker ps
: 1597056551:0;git pull origin master
: 1597056559:0;export CONFIG_SOURCE=http://localhost:8500
: 1597056568:0;export CONFIG_NAMESPACE=prile 
: 1597056572:0;uvicorn main:app --port 8888 --reload
: 1597056957:0;pip3 -V
: 1597056965:0;python3 -V
: 1597057076:0;rm -R .prile
: 1597057146:0;conda install python=3.7.7
: 1597057288:0;conda intall -c anaconda python=3.7.7
: 1597057297:0;conda install -c anaconda python=3.7.7
: 1597057323:0;conda search --full-name python
: 1597057498:0;conda install -c anaconda python=3.8
: 1597057562:0;conda update --all
: 1597057684:0;pip3 install psycopg2
: 1597057693:0;pip3 -V
: 1597062995:0;[200~sudo apt install software-properties-common~
: 1597063003:0;sudo apt install software-properties-common
: 1597063017:0;sudo add-apt-repository ppa:deadsnakes/ppa
: 1597063051:0;sudo apt update
: 1597063143:0;cd /tmp
: 1597063249:0;wget https://www.python.org/ftp/python/3.7.8/Python-3.7.8.tgz
: 1597063290:0;ls
: 1597063310:0;sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev wget
: 1597063332:0;tar -xf Python-3.7.8.tgz
: 1597063350:0;cd Python-3.7.8
: 1597063362:0;./configure --enable-optimizations
: 1597063423:0;sudo make altinstall
: 1597063555:0;cd
: 1597063558:0;python3 -V
: 1597063571:0;python3.7 -V
: 1597063579:0;python -V
: 1597063586:0;python3 --version
: 1597063592:0;python3.7 version
: 1597063599:0;python3.8 version
: 1597063608:0;python3.7 --version
: 1597063614:0;which python3
: 1597063621:0;which python3.7
: 1597063633:0;which python3.7.8
: 1597063638:0;sudo python -V
: 1597063648:0;sudo python3.7 -V
: 1597063693:0;rm -R .prile
: 1597063771:0;python3.7
: 1597063781:0;which python3.7
: 1597063795:0;sudo python3.7 -V
: 1597063814:0;sudo which python3.7
: 1597063899:0;source .prile/bin/activate
: 1597063901:0;ls
: 1597063902:0;clear
: 1597063907:0;pip3 -v
: 1597063911:0;pip3 -V
: 1597063924:0;python3 -V
: 1597063936:0;pip3 install requirements.txt
: 1597063944:0;pip3 install -r requirements.txt
: 1597064089:0;cd /tmp
: 1597064090:0;ls
: 1597064099:0;clear
: 1597064100:0;ls
: 1597064113:0;rm -R .
: 1597064162:0;rm -R *
: 1597064208:0;la
: 1597064209:0;ls
: 1597064216:0;rm -R Python-3.7.8
: 1597064230:0;sudo rm -R Python-3.7.8
: 1597064238:0;sudo rm -R *
: 1597064240:0;ls
: 1597064242:0;ls -la
: 1597064268:0;pip3 -V
: 1597064279:0;sudo pip3 install psycopg2
: 1597064332:0;sudo pip3 -V
: 1597064347:0;pip3 -V
: 1597064354:0;python3.7 -V
: 1597064397:0;rm -R .prile
: 1597064401:0;ls
: 1597064402:0;clear
: 1597064793:0;docker ps
: 1597066421:0;ls
: 1597066425:0;git status
: 1597066426:0;clear
: 1597066438:0;pip3 -V
: 1597066473:0;docker build -t app:v1
: 1597066799:0;docker build -t myapp ./
: 1597067044:0;git status
: 1597067063:0;docker ps
: 1597067074:0;docker images
: 1597067729:0;git pull origin master
: 1597107452:0;pip3 -V
: 1597107464:0;pip3 install upgrade pip
: 1597107479:0;pip3 install python-snappy
: 1597107787:0;date
: 1597109799:0;docker build -it uvicorn-server:v1 -f Dockerfile .
: 1597109807:0;docker build -t uvicorn-server:v1 -f Dockerfile .
: 1597114116:0;date
: 1597114118:0;cal 2020
: 1597114121:0;cal 2019
: 1597114883:0;git pull origin master
: 1597115849:0;clear
: 1597115854:0;docker ps
: 1597115860:0;docker-compose up -d
: 1597115866:0;docker ps
: 1597115896:0;ipconfig
: 1597115911:0;ifconfig
: 1597116141:0;docker compose
: 1597116150:0;telet
: 1597116161:0;telnet 192.168.1.103 8500
: 1597116233:0;clera
: 1597116239:0;clear
: 1597116245:0;sudo docker build -t event-processing:base
: 1597116297:0;sudo docker build -t event-processing:base .
: 1597116522:0;sudo  docker tag event-processing:base  146288359043.dkr.ecr.ap-southeast-1.amazonaws.com/event-processing:base
: 1597116536:0;sudo docker build -t event-processing:local-0.0.1 .
: 1597116675:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='prime/prile' -e CONFIG_SOURCE='http://192.168.1.103' event-processing:local-0.0.1
: 1597116684:0;docker ps | grep event 
: 1597116699:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597116737:0;docker exec -it 2e4ad8d6a79f /bin/sh
: 1597117056:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='/prile' -e CONFIG_SOURCE='http://19processing:local-0.0.1\
e
: 1597117058:0;docker ps
: 1597117070:0;docker rm -f 2e4ad8d6a79f
: 1597117073:0;docker ps
: 1597117123:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='/prile' -e CONFIG_SOURCE='http://192.168.1.103:8500' event-processing:local-0.0.1\
e
: 1597117189:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='/prile' -e CONFIG_SOURCE='http://192.168.1.103:8500' event-processing:local-0.0.1
: 1597117204:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='/prile' -e CONFIG_SOURCE='http://192.168.1.103:8501' event-processing:local-0.0.1
: 1597117217:0;sudo docker run -it -d  -p 8888:8889   -e CONFIG_NAMESPACE='/prile' -e CONFIG_SOURCE='http://192.168.1.103:8501' event-processing:local-0.0.1
: 1597117228:0;docker ps
: 1597117248:0;docker rm -f event-processing:local-0.0.1
: 1597117258:0;docker rm -f 0918f4da5d8f
: 1597117335:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='/prile' -e CONFIG_SOURCE='http://192.168.1.103:8500' event-processing:local-0.0.1
: 1597117344:0;docker ps
: 1597117375:0;docker exec -it 921c47265522 /bin/sh
: 1597117417:0;docker ps
: 1597117423:0;docker rm -f 921c47265522
: 1597117434:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='prile' -e CONFIG_SOURCE='http://192.168.1.103:8500' event-processing:local-0.0.1
: 1597117440:0;docker ps
: 1597117454:0;docker exec -it d6b79a3c4c4e /bin/sh
: 1597117777:0;docker exec -it event-processing_server_1 bash
: 1597118396:0;git checkout -b get_data_sample
: 1597118403:0;git status
: 1597120805:0;sudo apt-get install openvpn
: 1597120957:0;openvpn -version
: 1597120986:0;openvpn --config prime-chi.ovpn
: 1597121721:0;openvpn --config prime-chi.ovpn --auth-user-pass
: 1597121796:0;[200~openvpn --config client.ovpn --auth-user-pass --auth-retry interact~
: 1597121798:0;openvpn --config client.ovpn --auth-user-pass --auth-retry interact
: 1597121810:0;openvpn --config prime-chi.ovpn --auth-user-pass --auth-retry interact
: 1597122907:0;sudo apt-get --puge remove openvpn
: 1597122914:0;sudo apt-get --purge remove openvpn
: 1597122940:0;sudo apt-get install network-manager-openvpn-gnome
: 1597131707:0;docker ps
: 1597131910:0;docker ps -a
: 1597131993:0;docker images
: 1597136900:0;docker --help
: 1597136942:0;clear
: 1597136944:0;docker ps
: 1597137000:0;sudo docker build -t event-processing:local-0.0.2
: 1597137007:0;sudo docker build -t event-processing:local-0.0.2 .
: 1597137225:0;docker ps
: 1597137255:0;docker images
: 1597137718:0;sudo docker run -it -d 8888:8888 -e CONFIG_NAMESPACE='prile' -e CONFIG_SOURCE='http://localhost:8500' event-processing:local-0.0.2
: 1597137773:0;ifconfig
: 1597137786:0;localhost
: 1597138330:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='prile' -e CONFIG_SOURCE='http://localhost:8500' event-processing:local-0.0.2
: 1597138349:0;docker ps
: 1597138377:0;docker rm --help
: 1597138402:0;docker rm -f d6b79a3c4c4e
: 1597138405:0;docker ps
: 1597138413:0;docker ps -a
: 1597138424:0;docker --help
: 1597138467:0;docker ps -a
: 1597138478:0;docker rm e4334440e856
: 1597138489:0;docker ps -a
: 1597138499:0;docker rm 46aa1ee5e731
: 1597138514:0;docker ps -a
: 1597138557:0;docker rm e0d7089f9771
: 1597138566:0;docker rm b052738fd4b9
: 1597138568:0;docker ps -a
: 1597138589:0;docker rm dabd1638ce6e 5fe6591def28
: 1597138592:0;docker ps 
: 1597138612:0;docker images
: 1597138626:0;docker images --help
: 1597138641:0;docker images rm hello-world
: 1597138676:0;docker --help
: 1597138692:0;docker images
: 1597138761:0;docker rmi hello-world tiangolo/uvicorn-gunicorn mysql nginx mongo yandex/clickhouse-client event-processing
: 1597138776:0;docker images
: 1597138820:0;docker image --help
: 1597138889:0;docker ps
: 1597138903:0;docker images
: 1597138914:0;docker image prune
: 1597138923:0;docker images
: 1597138939:0;docker rmi event-processing
: 1597138957:0;docker rmi event-processing/local-0.0.2
: 1597138965:0;docker rmi 'event-processing/local-0.0.2'
: 1597138969:0;docker rmi 'event-processing'
: 1597138989:0;docker rmi cc5dd9ee3f7e
: 1597138992:0;docker images
: 1597139094:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='prile' -e CONFIG_SOURCE='http://192.168.1.103:8500' event-processing:local-0.0.1
: 1597139098:0;docker ps
: 1597139149:0;docker ps | grep event
: 1597139227:0;docker exec -it c3522c2f2fa1
: 1597139246:0;docker exec -it c3522c2f2fa1 /bin/sh
: 1597143253:0;clear
: 1597143257:0;docker ps
: 1597143513:0;docker exec -it event-processing_server_1 bash
: 1597153688:0;docker container --help
: 1597153759:0;docker --help
: 1597153829:0;docker container --help
: 1597153993:0;docker container run --name nginx nghix
: 1597154007:0;docker login
: 1597154031:0;docker container run --name nginx nginx
: 1597154101:0;docker images
: 1597154108:0;docker ps
: 1597154160:0;docker stop $(docker ps -aq)
: 1597154173:0;docker ps
: 1597154185:0;docker ps -a
: 1597154202:0;docker container run -d --name nginx nginx
: 1597154240:0;docker container start -d --name nginx nginx
: 1597154250:0;docker start --help
: 1597154283:0;docker container run --help
: 1597154329:0;docker container 
: 1597154335:0;docker container ls
: 1597154339:0;docker container ls -la
: 1597154346:0;docker container ls -a
: 1597154362:0;docker rm 5952078ec6d2
: 1597154369:0;docker ps -a
: 1597154386:0;docker container run -d --name nginx nginx
: 1597154390:0;docker ps
: 1597154486:0;docker container run -d --name mysql -e MYSQL_RANDOM_ROOT_PASSWORD=true mysql
: 1597154593:0;docker container --help
: 1597154616:0;docker container top --help
: 1597154638:0;docker container top mysql
: 1597154700:0;docker container top nginx
: 1597154802:0;docker container inspect mysql
: 1597154956:0;docker container stats --help
: 1597155047:0;docker container stast
: 1597155050:0;docker container stats
: 1597155259:0;docker container --help
: 1597155267:0;docker container run --help
: 1597155590:0;docker ps
: 1597155611:0;docker container run --name proxy nginx
: 1597155628:0;docker container run -i --name proxy1 nginx
: 1597155817:0;docker container run -it --name proxy2 nginx
: 1597155839:0;docker container run -it --name proxy3 nginx bash
: 1597155897:0;docker container run --help
: 1597156365:0;docker ps
: 1597156380:0;docker container ls -a
: 1597156627:0;docker container run -it --name ubuntu ubuntu
: 1597156710:0;docker ps
: 1597156713:0;docker ps -a
: 1597156801:0;docker container start --help
: 1597156853:0;docker container start -ai ubuntu
: 1597156945:0;docker container exec --help
: 1597157024:0;docker ps
: 1597157104:0;docker container exec -it mysql bash
: 1597157424:0;docker pull alpine
: 1597157437:0;docker image ls
: 1597157446:0;docker images ls
: 1597157450:0;docker images
: 1597157498:0;docker container run -it --name alpine alpine bash
: 1597157510:0;docker container run -it --name alpine alpine sh
: 1597157523:0;docker ps
: 1597157529:0;docker ps -a
: 1597157539:0;docker rm alpine
: 1597157543:0;docker ps
: 1597157545:0;docker ps -a
: 1597157559:0;docker container run -it alpine sh
: 1597157849:0;docker container port mysql
: 1597157854:0;docker ps
: 1597157863:0;docker container port nginx
: 1597157869:0;docker contaienr port --help
: 1597158406:0;docker container run --help
: 1597158457:0;docker container run -p 80:80 -d --name webhost nginx
: 1597158469:0;docker ps
: 1597158482:0;docker container port nginx
: 1597158496:0;docker rm nginx
: 1597158501:0;docker rm -f nginx
: 1597158506:0;docker ps -a
: 1597158508:0;docker ps
: 1597158535:0;docker container run -p 80:80 -d --name webhost nginx
: 1597158547:0;docker ps
: 1597158552:0;docker ps -a
: 1597158559:0;docker rm nginx
: 1597158586:0;docker rm 686bbfc6d206 53ad735860d4 760f66c5fcc1 9df14db30b41
: 1597158589:0;docker ps
: 1597158591:0;docker ps -a
: 1597158600:0;docker container run -p 80:80 -d --name webhost nginx
: 1597158636:0;docker ps
: 1597158664:0;docker container run -p 8081:8081 -d --name webhost nginx
: 1597158674:0;docker ps -a
: 1597158703:0;docker rm webhost
: 1597158713:0;docker ps -a
: 1597158805:0;docker container run -p 8081:8081 -d --name webhost nginx
: 1597158812:0;docker ps
: 1597159009:0;docker container inspect webhost
: 1597159028:0;docker container inspect webhost | grep IPAddress
: 1597159053:0;docker container port webhost
: 1597160243:0;docker --help
: 1597160251:0;docker --help | grep network
: 1597160258:0;docker network --help
: 1597160279:0;docker network ls
: 1597161260:0;docker network inspect bridge
: 1597161377:0;docker network ls
: 1597161437:0;docker network create my_app_net
: 1597161440:0;docker network s
: 1597161443:0;docker network ls
: 1597161585:0;docker container run -d --name new_nginx --network my_app_net nginx
: 1597161590:0;docker network ls
: 1597161612:0;docker network inspect new_nginx
: 1597161628:0;docker network inspect my_app_net
: 1597161641:0;docker network inspect brige
: 1597161649:0;docker network inspect bridge
: 1597161689:0;docker network --help
: 1597161894:0;docker network connect my_app_net webhost
: 1597161903:0;docker network inspect my_app_net
: 1597161912:0;docker network inspect bridge
: 1597162003:0;docker network connect my_app_net webhost
: 1597162008:0;docker network disconnect my_app_net webhost
: 1597162012:0;docker network inspect bridge
: 1597162022:0;docker network inspect my_app_net
: 1597196545:0;docker ps
: 1597196554:0;docker-compose -up -d
: 1597196569:0;docker-compose up -d
: 1597196778:0;docker ps
: 1597197097:0;docker images
: 1597197263:0;ifconfig
: 1597197317:0;docker run -it -d -p 8888:8888 -e CONFIG_NAMESPACE='prile' -e CONFIG_SOURCE='http://192.168.1.103:8500' event-processing:local-0.0.1
: 1597197328:0;docker ps | grep event
: 1597197370:0;docker exec -it bb5ed552bd9f /bin/sh
: 1597197949:0;clear
: 1597197952:0;docker ps
: 1597197965:0;docker rm - f bb5ed552bd9f
: 1597197979:0;docker stop bb5ed552bd9f
: 1597197993:0;docker ps
: 1597197999:0;docker ps -a
: 1597198042:0;docker rm bb5ed552bd9f c3522c2f2fa1
: 1597198047:0;docker ps -a
: 1597198053:0;docker image
: 1597198056:0;docker images
: 1597198107:0;docker rmi 85d15ff91c59 672d145b8fa0 85d15ff91c59
: 1597198119:0;docker images
: 1597198158:0;sudo docker rmi -f 85d15ff91c59 85d15ff91c59
: 1597198165:0;docker images
: 1597198198:0;docker container
: 1597198202:0;docker ps
: 1597198256:0;sudo docker build -t event-processing:base .
: 1597198353:0;sudo  docker tag event-processing:base  146288359043.dkr.ecr.ap-southeast-1.amazonaws.com/event-processing:base
: 1597198359:0;docker ps
: 1597198362:0;docker images
: 1597198385:0;sudo docker build -t event-processing:local-0.0.1 .
: 1597198644:0;sudo docker run -it -d  -p 8888:8888   -e CONFIG_NAMESPACE='prile' -e CONFIG_SOURCE='http://192.168.1.103:8500' event-processing:local-0.0.1
: 1597198652:0;docker ps
: 1597198680:0;docker exect -it fee79e97058f /bin/sh
: 1597198687:0;docker exec -it fee79e97058f /bin/sh
: 1597203394:0;docker ps
: 1597203420:0;docker stop fee79e97058f
: 1597203440:0;clear
: 1597203448:0;pip -V
: 1597203453:0;python -V
: 1597203460:0;which python 
: 1597203515:0;rm -R .prile
: 1597203516:0;ls
: 1597203518:0;ls -la
: 1597203609:0;pip -V
: 1597203629:0;pip install --no-cache-dir uvicorn gunicorn
: 1597203648:0;apt-get update
: 1597203655:0;sudo apt-get update
: 1597203670:0;apt-get install  libsnappy-dev -y
: 1597203678:0;sudo apt-get install  libsnappy-dev -y
: 1597203756:0;pip install python-snappy
: 1597203776:0;pip install -r requirements.txt
: 1597204266:0;export CONFIG_NAMESPACE=prile 
: 1597204290:0;export CONFIG_SOURCE=http://localhost:8500
: 1597204344:0;uvicorn main:app --reload
: 1597204486:0;pip install .
: 1597204496:0;uvicorn main:app --reload
: 1597204715:0;pip install -r requirements.txt
: 1597204959:0;pip install .
: 1597204975:0;uvicorn main:app --reload
: 1597205065:0;pip install -r requirements.txt
: 1597205096:0;pip3 install .
: 1597205149:0;pip install .
: 1597205310:0;pip install auto-remove
: 1597205323:0;pip install pip-autoremovew
: 1597205325:0;pip install pip-autoremove
: 1597205346:0;pip-autoremove pandas
: 1597205413:0;pip-autoremove setuptools
: 1597205427:0;pip -V
: 1597205444:0;pip install -r requirements.txt
: 1597205494:0;uvicorn main:app --reload
: 1597205557:0;pip install --upgrade pip
: 1597205567:0;pip3 -V
: 1597205572:0;which pip3
: 1597205582:0;which pip
: 1597205602:0;pip3 install -r requirements.txt
: 1597205609:0;pip3 install .
: 1597205620:0;uvicorn main:app --reload
: 1597205636:0;clear
: 1597206833:0;uvicorn main:app --reload
: 1597206981:0;pip3 install -r requirements.txt
: 1597206999:0;uvicorn main:app --reload
: 1597207029:0;pip3 install .
: 1597207036:0;uvicorn main:app --reload
: 1597225549:0;alembic history
: 1597225553:0;alembic current
: 1597225560:0;clear
: 1597278035:0;pip3 freeze
: 1597278152:0;pip3 freeze | grep 'pandas'
: 1597280369:0;pip show pandas
: 1597282206:0;pip3 install -r requirements.txt
: 1597282396:0;pip install psycopg2-binary --user
: 1597282639:0;pip3 install -r requirements.txt
: 1597282659:0;docker-compose up -d
: 1597282668:0;uvicorn main:app --reload
: 1597282675:0;export CONFIG_SOURCE=http://localhost:8500
: 1597282678:0;export CONFIG_NAMESPACE=prile 
: 1597282682:0;uvicorn main:app --reload
: 1597282835:0;pip3 install -r requirements.txt
: 1597282841:0;uvicorn main:app --reload
: 1597282903:0;pip3 install -r requirements.txt
: 1597282914:0;pip3 freeze
: 1597283007:0;wget https://download.teamviewer.com/download/linux/teamviewer_amd64.deb
: 1597283021:0;ls
: 1597283061:0;sudo apt-get install ./teamviewer_amd64.deb
: 1597283206:0;ls 
: 1597283223:0;pip list | grep pandas
: 1597283234:0;ls
: 1597283256:0;docker-compose up . 
: 1597283261:0;docker-compose up 
: 1597283271:0;clear
: 1597283272:0;ls
: 1597283307:0;python --version
: 1597283328:0;pip install -r requirements.txt
: 1597283338:0;pip install  . 
: 1597283374:0;export CONFIG_SOURCE='http://localhost:8500'
: 1597283387:0;export CONFIG_NAMESPACE='prile'
: 1597283402:0;python ./main.py
: 1597283453:0;pip install _bz2
: 1597283503:0;apt-get install libbz2-dev
: 1597283510:0;sudo apt-get install libbz2-dev
: 1597283526:0;python ./main.py
: 1597283603:0;python --version
: 1597283612:0;which python
: 1597283637:0;python3 ./main.py
: 1597283642:0;which python
: 1597283678:0;cd .prile/bin/python
: 1597283692:0;cd .prile/bin
: 1597283692:0;ls
: 1597283703:0;ll -a
: 1597283727:0;cd python3.7
: 1597283728:0;ls 
: 1597283815:0;cd /usr/lib/python3.7/lib-dynload
: 1597283816:0;ls 
: 1597283829:0;cd ..
: 1597283831:0;ls
: 1597283835:0;cd  ..
: 1597283843:0;cd python3
: 1597283845:0;ls
: 1597283847:0;cd ..
: 1597283853:0;cd python3.8
: 1597283854:0;ls
: 1597283862:0;cd lib-dynload
: 1597283863:0;ls
: 1597283938:0;sudp apt-get install bzip2-devel
: 1597283944:0;sudo apt-get install bzip2-devel
: 1597283980:0;sudo apt-get install libbz2-dev
: 1597283993:0;sudo apt-get install libbz2-dev --verbose
: 1597284028:0;python3
: 1597284045:0;clear
: 1597284077:0;cd /usr/lib/python3.7/lib-dynload
: 1597284078:0;ls
: 1597284104:0;cd ..
: 1597284106:0;ls
: 1597284107:0;cd ..
: 1597284108:0;ls
: 1597284116:0;cd python2.7
: 1597284116:0;ls
: 1597284122:0;cd lib-dynload/
: 1597284123:0;ls
: 1597284453:0;sudo apt-get update -y
: 1597284472:0;sudo apt-get install -y libbz2-dev
: 1597284517:0;dpkg =L libbz2-dev
: 1597284524:0;dpkg -L libbz2-dev
: 1597284634:0;pip uninstall pandas 
: 1597284661:0;cd ~
: 1597284691:0;pip3 install -r requirements.txt
: 1597284714:0;python ./main.py
: 1597284722:0;export CONFIG_NAMESPACE='prile'
: 1597284727:0;export CONFIG_SOURCE='http://localhost:8500'
: 1597284730:0;python ./main.py
: 1597284930:0;pip install .
: 1597284938:0;python ./main.py
: 1597284997:0;pip install .
: 1597285003:0;python ./main.py
: 1597285142:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597298984:0;git status
: 1597299179:0;git add README.md prile/. 
: 1597299181:0;git status
: 1597299295:0;git reset README.md prile/. 
: 1597299297:0;git status
: 1597299347:0;git checkout -b 'segment_analytics_api'
: 1597299350:0;git status
: 1597299356:0;git add README.md prile/. 
: 1597299359:0;git status
: 1597299444:0;git commit -m 'edited to release segment analytics api'
: 1597299446:0;git status
: 1597299456:0;git push origin segment_analytics_api
: 1597300008:0;git checkout master
: 1597300011:0;git status
: 1597300166:0;git checkout -b get_profile_api
: 1597300208:0;git checkout masetr
: 1597303084:0;git checkout master
: 1597303122:0;git branch -R get_profile_api
: 1597303132:0;git branch -D get_profile_api
: 1597303174:0;git checkout -b develop
: 1597303176:0;git status
: 1597303219:0;git merge segment_analytics_api
: 1597303269:0;git checkout -b feat/get_profile_api
: 1597309042:0;docker exec -it event-processing_server_1 bash
: 1597312825:0;git status
: 1597312862:0;git add prile/.
: 1597312863:0;git status
: 1597313012:0;git commit -m 'api get profile by tenant_id and anonymous_id'
: 1597313013:0;git status
: 1597313455:0;git push origin feat/get_profile_api
: 1597315805:0;git status
: 1597315826:0;git add prile/.
: 1597315830:0;git status
: 1597315852:0;git commit -m 'changed schema for profiles table'
: 1597315953:0;docker-compose up -d
: 1597317190:0;git status
: 1597317287:0;git commit -m 'use get_lastest_profile_by_id func'
: 1597317315:0;git add prile/.
: 1597317318:0;git status
: 1597317326:0;git commit -m 'use get_lastest_profile_by_id func'
: 1597317396:0;git push origin get_profile_api
: 1597317414:0;git push origin feat/get_profile_api
: 1597326201:0;git status
: 1597326216:0;git checkout develop
: 1597326226:0;git merge feat/get_profile_api
: 1597326432:0;git status
: 1597326442:0;git add prile/.
: 1597326467:0;git commit -m 'format file'
: 1597326492:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597327068:0;docker exec -it event-processing_server_1 bash
: 1597327494:0;git status
: 1597327562:0;git push origin develop
: 1597327582:0;git log
: 1597327690:0;git branch
: 1597330350:0;git status
: 1597330377:0;git checkout -b change_schema_profile
: 1597330379:0;git status
: 1597330389:0;git add .
: 1597330407:0;git commit -m 'changed profile schema'
: 1597330411:0;git checkout master
: 1597330420:0;git merge change_schema_profile
: 1597330600:0;clear
: 1597330627:0;pwd
: 1597330628:0;clear
: 1597330677:0;export CONFIG_SOURCE='http://localhost:8500'
: 1597330682:0;export CONFIG_NAMESPACE='prile'
: 1597330770:0;echo $CONFIG_NAMESPACE
: 1597330792:0;echo $CONFIG_SOURCE
: 1597330797:0;clear
: 1597331852:0;docker ps
: 1597331870:0;docker compose up -d
: 1597331876:0;docker-compose up -d
: 1597331885:0;docker ps
: 1597331886:0;clear
: 1597331895:0;docker ps
: 1597331896:0;clear
: 1597331905:0;uvicorn main:app --reload
: 1597331932:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597331969:0;echo $CONFIG_SOURCE
: 1597332060:0;export CONFIG_NAMESPACE='prile'
: 1597332063:0;export CONFIG_SOURCE='http://localhost:8500'
: 1597332124:0;echo $CONFIG_NAMESPACE
: 1597332135:0;echo $CONFIG_SOURCE
: 1597332140:0;clear
: 1597332144:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597333272:0;echo $CONFIG_SOURCE
: 1597335188:0;which python3
: 1597335198:0;which python
: 1597335203:0;python3 -V
: 1597335206:0;python -V
: 1597335217:0;python3
: 1597335332:0;sudo apt-get install libbz2-dev
: 1597335436:0;find libbz2-dev
: 1597335903:0;python -V
: 1597335908:0;which python
: 1597335913:0;python
: 1597335963:0;rm -R .prile
: 1597335964:0;ls
: 1597335998:0;which python
: 1597336006:0;python -V
: 1597336184:0;pip3 install requirements.txt
: 1597336189:0;pip3 install -rrequirements.txt
: 1597336263:0;clear
: 1597336270:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597336373:0;pip freeze
: 1597336392:0;pip freeze | grep 'prile'
: 1597336425:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597368641:0;git branch --help
: 1597368743:0;git branch -m MVP-218
: 1597368783:0;git push origin -u MVP-218
: 1597368816:0;git push origin --delete develop
: 1597368828:0;git status
: 1597368925:0;git branch -m [MVP218]
: 1597369211:0;git checkout master
: 1597369217:0;git status
: 1597369231:0;git checkout master
: 1597370125:0;clear
: 1597370369:0;docker-compose up -d
: 1597370374:0;clear
: 1597370510:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597379967:0;git checkout master
: 1597379976:0;git status
: 1597380006:0;git commit -m 'fix confict pandas and can run debug'
: 1597380010:0;git commit -am 'fix confict pandas and can run debug'
: 1597380014:0;git checkout master
: 1597380018:0;git pull origin master
: 1597380033:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597380819:0;sudo apt-add-repository ppa:audio-recorder/ppa
: 1597380839:0;[200~sudo apt-get update~
: 1597380841:0;sudo apt-get update
: 1597380850:0;sudo apt-get install audio-recorder
: 1597381730:0;git checkout MVP-218
: 1597382514:0;clear
: 1597382518:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597382793:0;git checkout master
: 1597382818:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597382845:0;git checkout MVP-218
: 1597384465:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597385486:0;git pull origin master
: 1597385507:0;git checkout master
: 1597385566:0;git revert
: 1597385580:0;git status
: 1597385688:0;git commit -am 'return a list of segment report instead one '
: 1597385695:0;git checkout master
: 1597385702:0;git pull origin master
: 1597389991:0;pip3 install -r requirements.txt
: 1597390175:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597412069:0;clear
: 1597412073:0;docker ps
: 1597412086:0;docker exec -it event-processing_server_1 bash
: 1597412162:0;git checkout events
: 1597412168:0;git checkout -b events
: 1597412179:0;git status
: 1597412191:0;git diff
: 1597419824:0;git status
: 1597419895:0;git checkout -b MVP-232-233
: 1597419898:0;git status
: 1597462042:0;docker-compose up -d
: 1597462048:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597468447:0;git status
: 1597468468:0;git add prile/.
: 1597468469:0;git status
: 1597468475:0;git diff
: 1597468530:0;git commit -m 'user_activity screen api base'
: 1597472824:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597484939:0;git status
: 1597485003:0;git add prile/. tests/. 
: 1597485007:0;git status
: 1597485036:0;git log
: 1597485066:0;git commit -m 'user activity APIs refactor'
: 1597485081:0;git push origin MVP-232-233
: 1597485471:0;git status
: 1597542658:0;git stastus
: 1597542661:0;git status
: 1597542783:0;git commit -am 'added events, events_summary_table, querys for api'
: 1597542787:0;git checkout master
: 1597542792:0;git merge events
: 1597627431:0;git status
: 1597630369:0;docker-compose up -d
: 1597630448:0;docker exec -it event-processing_server_1 bash
: 1597633499:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597634471:0;git status
: 1597634514:0;git add prile/.
: 1597634516:0;git status
: 1597634622:0;git commit -m 'deleted events summary table and aggregate direct from events' 
: 1597634632:0;git push origin MVP-232-233
: 1597651376:0;docker ps
: 1597655398:0;export REDIS_SERVER='localhost' --default 6379
: 1597655406:0;export REDIS_SERVER='localhost'
: 1597655413:0;export KAFKA_BOOTSTRAP_SERVERS='localhost:9092'
: 1597656022:0;faust -A prile/workflows/t_deserializer.py
: 1597656075:0;docker ps
: 1597656372:0;faust -A test prile/workflows worker -l info
: 1597656388:0;faust -A prile/workflows worker -l info
: 1597656409:0;faust -A prile/workflows/t_deserializer.py worker -l info
: 1597656498:0;git status
: 1597656523:0;git checkout master
: 1597656526:0;git status
: 1597656543:0;git checkout MVP-232-233
: 1597656545:0;git status
: 1597656565:0;git checkout -b 'test-faust'
: 1597656634:0;docker ps
: 1597656805:0;docker-compose up -d
: 1597656812:0;docker ps
: 1597657030:0;faust -A prile/workflows/t_deserializer -l info
: 1597657046:0;faust -A prile/workflows/t_deserializer worker -l info
: 1597657059:0;faust -A prile/workflows/t_deserializer.py worker -l info
: 1597657325:0;which faust
: 1597657340:0;faust worker --help
: 1597657401:0;faust -A prile/workflows/t_deserializer.py worker -l info
: 1597657475:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597657981:0;pip3 install .
: 1597657992:0;faust -A prile/workflows/t_deserializer.py worker -l info
: 1597658321:0;faust -A prile/workflows/segments_users_update worker -l info
: 1597658326:0;faust -A prile/workflows/segments_users_update/app.py worker -l info
: 1597658545:0;faust -A prile/workflows/segments_users_update worker -l info
: 1597658554:0;faust -A prile/workflows/segments_users_update/app worker -l info
: 1597658567:0;faust -A ./prile/workflows/segments_users_update/app worker -l info
: 1597658735:0;pip3 run 
: 1597658740:0;run
: 1597658903:0;pipenv run faust -A prile/workflows/segments_users_update/app worker -l info
: 1597659014:0;faust -A prile/workflows/segments_users_update/app worker -l info
: 1597659173:0;faust -A prile/workflows/segments_users_update worker -l info
: 1597659854:0;which faust
: 1597659874:0;which python3
: 1597659879:0;python3
: 1597659965:0;faust -A 'prile/workflows/segments_users_update' worker -l info
: 1597659978:0;faust -A prile/workflows/segments_users_update/app.py worker -l info
: 1597660008:0;python3 run faust -A prile/workflows/segments_users_update/app.py worker -l info
: 1597660033:0;pip3 run faust -A prile/workflows/segments_users_update/app.py worker -l info
: 1597660040:0;run faust -A prile/workflows/segments_users_update/app.py worker -l info
: 1597660070:0;faust run prile/workflows/segments_users_update/app.py workder -l info
: 1597660160:0;python3 setup.py
: 1597660196:0;python setup.py sdist bdist_wheel
: 1597660332:0;pip3
: 1597660334:0;pip3 -V
: 1597660343:0;pip3 install -r requirements.txt
: 1597660368:0;python3 setup.py sdist bdist_wheel
: 1597660377:0;python3 setup.py
: 1597660883:0;which pipenv
: 1597660903:0;sudo faust run prile/workflows/segments_users_update/app.py workder -l info
: 1597660919:0;sudo faust -A prile/workflows/segments_users_update/app.py worker -l info
: 1597660928:0;faust -A prile/workflows/segments_users_update/app.py worker -l info
: 1597661083:0;faust -A prile/workflows/segments_users_update:app worker -l info
: 1597661222:0;faust
: 1597661239:0;which faust
: 1597661259:0;prile
: 1597661266:0;prile run 
: 1597661279:0;prile run faust
: 1597661365:0;faust -A prile/workflows/segments_users_update:app worker -l
: 1597661405:0;faust -A prile/workflows/segments_users_update/app.py worker -l
: 1597661497:0;faust -A prile/workflows/segments_users_update/app worker -l
: 1597661615:0;faust -A prile/workflows/t_deserializer.py worker -l info
: 1597662103:0;faust -A prile/workflows/segments_users_update/app.py.app worker -l
: 1597662109:0;faust -A prile/workflows/segments_users_update/app.app worker -l
: 1597662122:0;faust -A prile/workflows/segments_users_update/a
: 1597662128:0;prile/workflows/segments_users_update/app.app worker -l
: 1597662155:0;faust -A prile/workflows/segments_users_update/app:app worker -l
: 1597662163:0;faust -A prile/workflows/segments_users_update/app.py/app worker -l
: 1597662170:0;faust -A prile/workflows/segments_users_update/app.py.app worker -l
: 1597662173:0;faust -A prile/workflows/segments_users_update/app.py:app worker -l
: 1597662215:0;faust -A prile/workflows/segments_users_update/app.py app worker -l
: 1597662233:0;faust -A prile/workflows/segments_users_update/app.py:app worker -l
: 1597662284:0;faust -A (prile/workflows/segments_users_update/app.py)app worker -l
: 1597662287:0;faust -A (prile/workflows/segments_users_update/app.py).app worker -l
: 1597662303:0;faust -A prile/workflows/segments_users_update/app.py:app worker -l info
: 1597662321:0;faust -A prile/workflows/segments_users_update/app.app worker -l
: 1597662379:0;faust -A prile/workflows/segments_users_update/app:app worker -l
: 1597662404:0;faust -A prile/workflows/segments_users_update/app : app worker -l
: 1597662429:0;pwd
: 1597662467:0;faust -A ./prile/workflows/segments_users_update/app.app worker -l
: 1597662476:0;faust -A ./prile/workflows/segments_users_update/app worker -l
: 1597662499:0;pwd
: 1597662560:0;cd prile/workflows
: 1597662578:0;faust -A segments_users_update/app worker -l
: 1597662585:0;faust -A segments_users_update/app.app worker -l
: 1597662595:0;faust -A segments_users_update/app.py
: 1597662601:0;faust -A segments_users_update/app.py worker -l
: 1597662630:0;cd ..
: 1597662644:0;faust -A prile.workflows.segments_users.app.segment_update .app worker -l
: 1597662726:0;faust -A prile/workflows/segments_users_update .app worker -l
: 1597662758:0;faust -A prile.workflows.segments_users_update.app worker -l
: 1597663233:0;faust -A prile.workflows.segments_users_updat
: 1597663234:0;faust -A prile.workflows.segments_users_update.app worker -l
: 1597664038:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597664797:0;faust -A prile.workflows.segments_users_update.app send input  '{"segment":"segment2", "state": "in", "user":"user2", "at":"2020-07-10 00:00:00"}'
: 1597665068:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597672709:0;faust -A prile.workflows.segments_users_update.app send input  '{"segment":"segment2", "state": "in", "user":"user2", "at":"2020-07-10 00:00:00"}'
: 1597672735:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597672741:0;faust -A prile.workflows.segments_users_update.app send input  '{"segment":"segment2", "state": "in", "user":"user2", "at":"2020-07-10 00:00:00"}'
: 1597675760:0;docker exec -it event-processing_server_1 bash
: 1597678366:0;faust -A prile.workflows.segments_users_update.app send input  '{"segment":"segment2", "state": "in", "user":"user2", "at":"2020-07-10 00:00:00"}'
: 1597678475:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597678552:0;faust -A prile.workflows.segments_users_update.app send input  '{"segment":"segment2", "state": "in", "user":"user2", "at":"2020-07-10 00:00:00"}'
: 1597678596:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597678604:0;faust -A prile.workflows.segments_users_update.app send input  '{"segment":"segment2", "state": "in", "user":"user2", "at":"2020-07-10 00:00:00"}'
: 1597678666:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597678711:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597678717:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597678770:0;docker ps
: 1597678957:0;docker-compose up -d
: 1597678987:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597679043:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597679085:0;docker ps
: 1597679100:0;docker-compose up -d
: 1597679110:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597679297:0;faust -A prile.workflows.segments_userer":"user2", "at":"2020-07-10 00:00:00"}'\
quit()
: 1597679298:0;faust -A prile.workflows.segments_users_update.app send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597679428:0;faust -A hello_world send @greet "Hello Faust"
: 1597679508:0;faust -A prile.workflows.segments_users_update.app send @greet "Hello faust"
: 1597679583:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597679588:0;faust -A prile.workflows.segments_users_update.app send @greet "Hello faust"
: 1597679631:0;faust -A prile.workflows.segments_users_update.app send greetings "Hello Fuast"
: 1597679901:0;faust -A prile.workflows.segments_users_update.app send greetings ">>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>Hello Fuast"
: 1597680067:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597680072:0;faust -A prile.workflows.segments_users_update.app send greetings ">>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>Hello Fuast"
: 1597680190:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597680194:0;faust -A prile.workflows.segments_users_update.app send greetings ">>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>Hello Fuast"
: 1597680209:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597680212:0;faust -A prile.workflows.segments_users_update.app send greetings ">>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>Hello Fuast"
: 1597680264:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597680267:0;faust -A prile.workflows.segments_users_update.app send greetings ">>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>Hello Fuast"
: 1597680375:0;faust -A prile.workflows.segments_users_update.app send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597680425:0;faust -A prile.workflows.segments_users_update.app send @process  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597680453:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597680456:0;faust -A prile.workflows.segments_users_update.app send @process  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597680469:0;faust -A prile.workflows.segments_users_update.app send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597680541:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597680545:0;faust -A prile.workflows.segments_users_update.app send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597680892:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597680982:0;faust -A prile.workflows.segments_users_update.app send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597681304:0;faust -A prile.workflows.segments_users_update.agents send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597681334:0;faust -A prile.workflows.segments_users_update send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597681364:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597681368:0;faust -A prile.workflows.segments_users_update send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597681416:0;faust -A prile.workflows.segments_users_update worker -l info
: 1597681422:0;faust -A prile.workflows.segments_users_update send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597681497:0;faust -A prile.workflows.segments_users_update worker -l info
: 1597681616:0;faust -A prile.workflows.segments_users_update send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597681630:0;faust -A prile.workflows.segments_users_update.app send greetings ">>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>Hello Fuast"
: 1597681640:0;faust -A prile.workflows.segments_users_update send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597682126:0;python3 prile.workflows.segments_users_update agents
: 1597682180:0;python3 prile.workflows.segments_users_update.app agents
: 1597682189:0;python3 prile/workflows/segments_users_update/app agents
: 1597682219:0;python3 prile/workflows/segments_users_update/app.py agents
: 1597682355:0;prile/workflows/segments_users_update/app.py agents
: 1597719321:0;docker-compose up -d
: 1597719333:0;docker ps
: 1597719343:0;docker-compose up -d
: 1597719356:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597719384:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597719470:0;faust -A prile.workflows.segments_users_update send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597719811:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597721777:0;faust -A prile.workflows.segments_users_update send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597721811:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597721861:0;faust -A prile.workflows.segments_users_update.app send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597721918:0;faust -A prile.workflows.segments_users_update.app send @process  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597721965:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597721969:0;faust -A prile.workflows.segments_users_update.app send @process  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597722037:0;faust -A prile.workflows.segments_users_update.app send @greet  'hello >>>>>>>'
: 1597722044:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597722046:0;faust -A prile.workflows.segments_users_update.app send @greet  'hello >>>>>>>'
: 1597722067:0;faust -A prile.workflows.segments_users_update.app send greetings  'hello >>>>>>>'
: 1597722083:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597722102:0;faust -A prile.workflows.segments_users_update.app send greetings  'hello >>>>>>>'
: 1597722244:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597722250:0;faust -A prile.workflows.segments_users_update.app send greetings  'hello >>>>>>>'
: 1597722285:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597722290:0;faust -A prile.workflows.segments_users_update.app send greetings  'hello >>>>>>>'
: 1597722306:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597723692:0;faust -A prile.workflows.segments_users_update.app worker -
: 1597723742:0;faust -A prile.workflows.segments_users_update.app send input  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597723767:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597723789:0;faust -A prile.workflows.segments_users_update.app send "input123"  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597724498:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597724698:0;export APP_PATH = 'prile.workflows.segments_users_update.app'
: 1597724704:0;echo APP_PATH
: 1597724709:0;echo $APP_PATH
: 1597724730:0;export APP_PATH = "prile.workflows.segments_users_update.app"
: 1597724803:0;echo $APP_PATH
: 1597724862:0;faust -A $APP_PATH wo
: 1597724872:0;faust -A $APP_PATH worker -l info
: 1597724881:0;faust -A $(APP_PATH) worker -l info
: 1597724929:0;$(APP_PATH)
: 1597724938:0;faust -A $APP_PATH worker -l info
: 1597724986:0;faust -A $(echo $APP_PATH) worker -l info
: 1597724990:0;faust -A (echo $APP_PATH) worker -l info
: 1597725031:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597725532:0;faust -A prile.workflows.segments_users_update.app page_views '{"id": "foo", "user": "bar"}'
: 1597725546:0;faust -A prile.workflows.segments_users_update.app send page_views '{"id": "foo", "user": "bar"}'
: 1597725578:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597725583:0;faust -A prile.workflows.segments_users_update.app send page_views '{"id": "foo", "user": "bar"}'
: 1597725602:0;faust -A prile.workflows.segments_users_update.app send page_views '{"id": "foo"}'
: 1597725620:0;faust -A prile.workflows.segments_users_update.app send page_views '{"id": "foo", "user":"bar"}'
: 1597725629:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597725632:0;faust -A prile.workflows.segments_users_update.app send page_views '{"id": "foo", "user":"bar"}'
: 1597725678:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597725706:0;faust -A prile.workflows.segments_users_update.app send page_views '{"id": "foo", "user":"bar"}'
: 1597725713:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597725723:0;faust -A prile.workflows.segments_users_update.app send page_views '{"id": "foo", "user":"bar", "value":1}'
: 1597726101:0;..................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................
: 1597726102:0;clear
: 1597727330:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597727564:0;faust -A prile.workflows.segments_users_update.app worker -
: 1597727577:0;faust -A prile.workflows.segments_users_update.app send "input123"  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597727641:0;sudo docker ps 
: 1597727685:0;sudo docker exec -it 03bfe90be2ea /bin/sh
: 1597727858:0;faust -A prile.workflows.segments_users_update.app send "input123"  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597728057:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597728069:0;faust -A prile.workflows.segments_users_update.app send "input123"  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597728254:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597728260:0;faust -A prile.workflows.segments_users_update.app send "input123"  '{"tenant_id",1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597728344:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597728354:0;faust -A prile.workflows.segments_users_update.app send "input123"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597728526:0;clear
: 1597733096:0;pwd
: 1597733097:0;clear
: 1597733122:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597733248:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597739018:0;git status
: 1597739062:0;git add prile/.
: 1597739066:0;git status
: 1597739087:0;git add README.md
: 1597739111:0;git commit -m 'stream procesing edit for runable'
: 1597739118:0;git checkout master
: 1597739123:0;git pull origin master
: 1597739176:0;git branch
: 1597739211:0;git checkout feat/get_profile_api
: 1597739225:0;git status
: 1597739235:0;git checkout feat/get_profile_api
: 1597739294:0;git checkout -b MVP-244
: 1597740557:0;docker exec -it event-processing_server_1 bash
: 1597760809:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597760820:0;docker-compose up -d
: 1597760828:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597762563:0;docker exec -it event-processing_server_1 bash
: 1597765792:0;cd python
: 1597765805:0;ls
: 1597765808:0;ls -la
: 1597765814:0;cd ..
: 1597765819:0;cd python
: 1597765824:0;cd .learn-python
: 1597765825:0;ls
: 1597765827:0;cd bin
: 1597765827:0;ls
: 1597765833:0;./activate
: 1597765838:0;sudo ./activate
: 1597765901:0;clear
: 1597765927:0;pip3 install pydantic
: 1597771343:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597802171:0;git status
: 1597802272:0;git add prile/.
: 1597802277:0;git add tests/.
: 1597802278:0;git status
: 1597803528:0;docker-compose up -d
: 1597803536:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597804546:0;docker ps
: 1597807619:0;git status
: 1597807646:0;git commit -m 'get profile details api base'
: 1597807650:0;git sttus
: 1597807652:0;git status
: 1597816247:0;docker exec -it event-processing_server_1 bash
: 1597816787:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597817475:0;git status
: 1597817480:0;git add prile/
: 1597817484:0;git status
: 1597817569:0;git commit -m "refactor get profile details and move user_activity to user_profile"
: 1597817571:0;git status
: 1597817579:0;git push origin MVP-244
: 1597822219:0;git branch
: 1597822228:0;git checkout test-faust
: 1597826877:0;docker ps
: 1597826882:0;docker-compose up -d
: 1597826910:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597827062:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597827094:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597827097:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597827194:0;docker ps
: 1597827203:0;docker ps -a
: 1597827225:0;docker exec -it 03bfe90be2ea /bin/sh
: 1597827258:0;sudo docker exec -it 03bfe90be2ea /bin/sh
: 1597841624:0;docker ps
: 1597841943:0;sudo docker exec -it 03bfe90be2ea /bin/bash
: 1597842416:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 00:00:00"}'
: 1597842422:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 10:00:00"}'
: 1597842485:0;clear
: 1597842726:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 10:00:00"}'
: 1597842740:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597842743:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 10:00:00"}'
: 1597842998:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597843003:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"2020-07-10 10:00:00"}'
: 1597843470:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597843477:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597843481:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597844456:0;ifconfig
: 1597886087:0;clear
: 1597886146:0;sudo docker exec -it 03bfe90be2ea /bin/bash
: 1597887477:0;docker ps
: 1597888549:0;sudo docker exec -it 03bfe90be2ea /bin/bash
: 1597976811:0;docker-compose up -d
: 1597976825:0;docker ps
: 1597976849:0;docker-compose up -d
: 1597976853:0;docker ps
: 1597976868:0;docker ps --help
: 1597976876:0;docker ps -q
: 1597976904:0;sudo docker exec -it 03bfe90be2ea /bin/bash
: 1597978193:0;clear
: 1597978420:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597978440:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597978549:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597978552:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597978609:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597978614:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597978815:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597978818:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597980820:0;git checkout master
: 1597980828:0;git status
: 1597980840:0;git add prile/.
: 1597980859:0;git commit -m 'test stream kafka'
: 1597980863:0;git checkout master
: 1597980868:0;git pull origin master
: 1597981128:0;clear
: 1597981131:0;git status
: 1597981155:0;git branch -D test-faust
: 1597981161:0;git checkout test-faust
: 1597981169:0;git checkout -b test-faust
: 1597981607:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597981673:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597981723:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s2", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597981764:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597981789:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597981795:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597981798:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597981817:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597981819:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597981945:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597981947:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597981995:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597981998:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597982030:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597982035:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597982173:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597982175:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597982202:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597982204:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597982243:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597982244:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597982839:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597982842:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597982873:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597982875:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597982910:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597982912:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1597983028:0;git status
: 1597983037:0;git add prile/.
: 1597983055:0;git commit -m 'fixing error type'
: 1597983059:0;git checkout master
: 1597983082:0;git checkout -b fix_identity_schema
: 1597983091:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1597986052:0;git status
: 1597986079:0;git add .pri
: 1597986083:0;git add prile/.
: 1597986120:0;git commit -m 'fixed format of indentity'
: 1597986128:0;git push origin fix_identity_schema
: 1597986319:0;which pip3
: 1597990424:0;pip3 install aredis
: 1597990456:0;docker ps
: 1597991313:0;docker exect -it a2b0f45e64ea /bin/bash
: 1597991334:0;sudo docker exec -it 03bfe90be2ea /bin/bash
: 1597991373:0;sudo docker exec -it 45e64eabe2ea /bin/bash
: 1597991379:0;docker ps
: 1597991390:0;sudo docker exec -it a2b0f45e64ea  /bin/bash
: 1597998013:0;sudo docker exec -it a2b0f45e64ea. But I'm really curious to understand why this happens only with docker images that use Tini as ENTRYPOINT.  /bin/bash\
\

: 1597998031:0;sudo docker exec -it a2b0f45e64ea. But I'm really curious to understand why this happens only with docker images that use Tini as ENTRYPOINT --user=chile  /bin/bash\

: 1597998053:0;sudo docker exec -it a2b0f45e64ea --user=chile  /bin/bash
: 1597998076:0;who am i
: 1597998079:0;whoami
: 1597998465:0;sudo docker exec -it a2b0f45e64ea bash
: 1597999339:0;git status
: 1597999347:0;git checkout test-faust
: 1597999374:0;clear
: 1597999433:0;sudo docker exec -it a2b0f45e64ea bash
: 1597999645:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1597999973:0;echo $CONFIG_SOURCE
: 1598000070:0;echo $REDIS_SERVER
: 1598000188:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598000302:0;echo $CONFIG_SOURCE
: 1598000340:0;export REDIS_SERVER = 'localhost'
: 1598000352:0;export REDIS_SERVER='localhost'
: 1598000355:0;echo $REDIS_SERVER
: 1598000365:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598000789:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836800"}'
: 1598001412:0;docker ps
: 1598001448:0;sudo docker exec -it a2b0f45e64ea bash
: 1598002014:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598002346:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"'
: 1598002355:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598002404:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598002430:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598002530:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598002535:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598002634:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598002638:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598002965:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598002968:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003052:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003056:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003083:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003086:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003265:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003268:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003397:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003404:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003469:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003471:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003489:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003492:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003511:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003514:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003525:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user2", "at":"1577836801"}'
: 1598003535:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598003538:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user2", "at":"1577836801"}'
: 1598003545:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598003780:0;docker ps
: 1598003805:0;docker exec -it 03bfe90be2ea bash
: 1598004707:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598004711:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598004807:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598004811:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598005278:0;docker ps
: 1598005296:0;docker exec -it 767b60f7610e bash
: 1598005330:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598005333:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598005614:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598005618:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598007721:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598007723:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598007752:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598007754:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598008115:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598008118:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598008162:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598008164:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598008499:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598008505:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598008575:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598008578:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598009149:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598009151:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598009253:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598009255:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598009332:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598009335:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598009449:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598009452:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598009604:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598009607:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598009738:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598009740:0;faust -A prile.workflows.segments_users_update.app send "input"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1577836801"}'
: 1598011331:0;git status
: 1598011339:0;git add prile/
: 1598011359:0;git commit -m "[Streaming] Refactor"
: 1598011363:0;git status
: 1598011370:0;git stash 
: 1598011381:0;git checkout master
: 1598011405:0;git checkout -b MVP-Profile
: 1598011706:0;git status
: 1598011722:0;git checkout master
: 1598011728:0;git pull origin master
: 1598011774:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598011873:0;git status
: 1598011885:0;git git status
: 1598011891:0;git branch fix_identity_schema
: 1598011910:0;git checkout fix_identity_schema
: 1598012349:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598066929:0;docker-compose up -d
: 1598066936:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598068994:0;sudo docker exec -it a2b0f45e64ea bash
: 1598069014:0;docker ps
: 1598069054:0;docker exec -it 767b60f7610e /bin/bash
: 1598073410:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598073911:0;git status
: 1598076370:0;docker-compose up -d
: 1598076382:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598076500:0;git status
: 1598077419:0;git add .
: 1598077421:0;git status
: 1598077950:0;git commit -m "added filter by propeties into request api'\
"
: 1598077953:0;git status
: 1598078022:0;git push origin fix_identity_schema
: 1598078041:0;git status
: 1598078065:0;git branch -D MVP-Profile
: 1598078072:0;git branch
: 1598078091:0;git merge test-faust
: 1598078114:0;git stash
: 1598078116:0;git status
: 1598078148:0;git checkout -b users_segments_update
: 1598078154:0;git merge test-faust
: 1598078462:0;docker ps
: 1598080033:0;docker exec -it a2b0f45e64ea bash
: 1598082924:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598083162:0;docker ps
: 1598083174:0;docker exec -it 767b60f7610e /bin/bash
: 1598083244:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"user1", "at":"1598083220"}'
: 1598083529:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598083546:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083220"}'
: 1598083828:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598083831:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083220"}'
: 1598083929:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598083933:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083220"}'
: 1598084009:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598084012:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083220"}'
: 1598084321:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598086902:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083220"}'
: 1598086913:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s1", "state": "in", "user2":"a1", "at":"1598083220"}'
: 1598087055:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598087063:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1"\

: 1598087154:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s100", "state": "in", "user":"a100", "at":"1598083220"}'
: 1598087158:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598087552:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598087581:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s105", "state": "in", "user":"a105", "at":"1598083220"}'
: 1598087586:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s105", "state": "in", "user":"a106", "at":"1598083230"}'
: 1598087704:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598087711:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s110", "state": "in", "user":"a110", "at":"1598083220"}'
: 1598087717:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s110", "state": "in", "user":"a111", "at":"1598083230"}'
: 1598087771:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598087776:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s110", "state": "in", "user":"a110", "at":"1598083220"}'
: 1598087781:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s110", "state": "in", "user":"a111", "at":"1598083230"}'
: 1598087887:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s210", "state": "in", "user":"210", "at":"1598083220"}'
: 1598087892:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s210", "state": "in", "user":"211", "at":"1598083230"}'
: 1598087934:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s210", "state": "in", "user":"212", "at":"1598083220"}'
: 1598087984:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s211", "state": "in", "user":"212", "at":"1598083220"}'
: 1598088011:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s213", "state": "in", "user":"212", "at":"1598083220"}'
: 1598088017:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s214", "state": "in", "user":"212", "at":"1598083220"}'
: 1598088079:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s215", "state": "in", "user":"212", "at":"1598083220"}'
: 1598088086:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s216", "state": "in", "user":"212", "at":"1598083220"}'
: 1598088143:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s217", "state": "in", "user":"212", "at":"1598083220"}'
: 1598088150:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s218", "state": "in", "user":"212", "at":"1598083220"}'
: 1598088267:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s300", "state": "in", "user":"a300", "at":"1598083220"}'
: 1598088271:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s301", "state": "in", "user":"a300", "at":"1598083230"}'
: 1598088505:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s400", "state": "in", "user":"a400", "at":"1598083220"}'
: 1598088511:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s401", "state": "in", "user":"a400", "at":"1598083230"}'
: 1598088579:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598088791:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s500", "state": "in", "user":"a500", "at":"1598083220"}'
: 1598088795:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s501", "state": "in", "user":"a500", "at":"1598083230"}'
: 1598088886:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598088899:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s600", "state": "in", "user":"a600", "at":"1598083220"}'
: 1598088904:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s601", "state": "in", "user":"a600", "at":"1598083230"}'
: 1598089387:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598089446:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s10", "state": "in", "user":"a0", "at":"1598083220"}'
: 1598089452:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s10", "state": "in", "user":"a1", "at":"1598083240"}'
: 1598089599:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598089616:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s11", "state": "in", "user":"a0", "at":"1598083270"}'
: 1598089621:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s11", "state": "in", "user":"a1", "at":"1598083280"}'
: 1598089810:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598089846:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s12", "state": "in", "user":"a12", "at":"1598083270"}'
: 1598089851:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s12", "state": "in", "user":"a13", "at":"1598083280"}'
: 1598090243:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598090297:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s18", "state": "in", "user":"a18", "at":
: 1598090299:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s18", "state": "in", "user":"a18", "at":"1598083270"}'
: 1598090304:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s18", "state": "in", "user":"a18", "at":"1598083280"}'
: 1598090369:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s18", "state": "in", "user":"a19", "at":"1598083290"}'
: 1598090381:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s18", "state": "in", "user":"a20", "at":"1598083390"}'
: 1598090918:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598090957:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s20", "state": "in", "user":"a20", "at":"1598083390"}'
: 1598090962:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s20", "state": "in", "user":"a21", "at":"1598083480"}'
: 1598091094:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a201", "at":"1598083390"}'
: 1598091099:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a202", "at":"1598083480"}'
: 1598091314:0;docker ps
: 1598092170:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598092184:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a201", "at":"1598083390"}'
: 1598092269:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598092293:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598092413:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598092429:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598092436:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a201", "at":"1598083390"}'
: 1598092443:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a202", "at":"1598083480"}'
: 1598092495:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598092753:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a201", "at":"1598083390"}'
: 1598092762:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a202", "at":"1598083480"}'
: 1598092810:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598093107:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598093110:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598093124:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a203", "at":"1598083480"}'
: 1598093690:0;docker-compose up -d
: 1598093715:0;docker ps
: 1598093724:0;docker-compose up -d
: 1598093727:0;docker ps
: 1598093754:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598093786:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a201", "at":"1598083390"}'
: 1598093818:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s21", "state": "in", "user":"a202", "at":"1598083480"}'
: 1598094073:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598096043:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598096057:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598096084:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598096531:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598096538:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598096554:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598096561:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598097072:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598097080:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598097085:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598097378:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598097386:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598097390:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598097420:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598097438:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":4, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598097443:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":4, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598097508:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598097512:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "in", "user":"a102", "at":"1598083231"}'
: 1598097517:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "in", "user":"a103", "at":"1598083232"}'
: 1598097521:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "in", "user":"a104", "at":"1598083233"}'
: 1598097526:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "in", "user":"a105", "at":"1598083234"}'
: 1598097638:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "out", "user":"a101", "at":"1598083330"}'
: 1598097642:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "out", "user":"a102", "at":"1598083331"}'
: 1598097646:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "out", "user":"a103", "at":"1598083332"}'
: 1598097757:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598097766:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "out", "user":"a101", "at":"1598083330"}'
: 1598097774:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s100", "state": "out", "user":"a102", "at":"1598083331"}'
: 1598097921:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s700", "state": "in", "user":"a700", "at":"1598083330"}'
: 1598097927:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s700", "state": "in", "user":"a701", "at":"1598083331"}'
: 1598097932:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s701", "state": "in", "user":"a700", "at":"1598083332"}'
: 1598097938:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s701", "state": "in", "user":"a701", "at":"1598083333"}'
: 1598097944:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s701", "state": "in", "user":"a702", "at":"1598083334"}'
: 1598098088:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s700", "state": "out", "user":"a700", "at":"1598083430"}'
: 1598098093:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s700", "state": "out", "user":"a701", "at":"1598083431"}'
: 1598098098:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s701", "state": "out", "user":"a700", "at":"1598083432"}'
: 1598098102:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s701", "state": "out", "user":"a701", "at":"1598083433"}'
: 1598098107:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s701", "state": "out", "user":"a702", "at":"1598083434"}'
: 1598099352:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s700", "state": "out", "user":"a700", "at":"1598083430"}'
: 1598099405:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s700", "state": "in", "user":"a701", "at":"1598083431"}'
: 1598099480:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598099490:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s700", "state": "in", "user":"a700", "at":"1598083430"}'
: 1598099495:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s700", "state": "in", "user":"a701", "at":"1598083431"}'
: 1598099500:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s701", "state": "in", "user":"a700", "at":"1598083432"}'
: 1598099504:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s701", "state": "in", "user":"a701", "at":"1598083433"}'
: 1598099523:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598099535:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a100", "at":"1598083230"}'
: 1598099540:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s100", "state": "in", "user":"a101", "at":"1598083230"}'
: 1598099545:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s700", "state": "in", "user":"a700", "at":"1598083430"}'
: 1598099550:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":7, "segment":"s700", "state": "in", "user":"a701", "at":"1598083431"}'
: 1598100229:0;env
: 1598100249:0;env | config
: 1598100254:0;env | grep config
: 1598100259:0;env | grep CONFIG
: 1598100608:0;pip install aiomonitor
: 1598100616:0;pip install -U faust[debug]
: 1598100648:0;pwd
: 1598100649:0;ls 
: 1598100657:0;cd segments_user_update-data
: 1598100657:0;ls 
: 1598100665:0;cd ..
: 1598100665:0;ls
: 1598100666:0;cd ..
: 1598100668:0;ls
: 1598100669:0;ls 
: 1598100681:0;cd prime/
: 1598100682:0;ls
: 1598100685:0;cd ..
: 1598100687:0;ls
: 1598100690:0;cd event-processing
: 1598100690:0;ls
: 1598100694:0;cd prile
: 1598100695:0;ls
: 1598100699:0;cd workflows/segments_users_update
: 1598100700:0;ls
: 1598100716:0;faust -A app.py --debug worker -l infor
: 1598100873:0;ls 
: 1598100879:0;pip install .
: 1598100892:0;clear
: 1598100899:0;faust -A app.py --debug worker -l infor
: 1598100931:0;ls
: 1598100962:0;faust -A app.py:app --debug worker -l infor
: 1598100994:0;faust -A :app --debug worker -l infor
: 1598100999:0;faust -A app --debug worker -l infor
: 1598101017:0;faust -A app --debug worker -l info
: 1598101271:0;git status
: 1598101292:0;git stastus
: 1598101295:0;git status
: 1598101300:0;git add .
: 1598101321:0;git commit -m 'user_segments_update debuging...'
: 1598101328:0;git push origin users_segments_update
: 1598149059:0;cd ..
: 1598149059:0;ls
: 1598149064:0;cd support-event-processing
: 1598149064:0;ls
: 1598149072:0;python3
: 1598149753:0;cd ..
: 1598149862:0;python3
: 1598149910:0;pip frezee | grep sqlalchemy
: 1598149919:0;pip freezee | grep sqlalchemy
: 1598149928:0;pip freeze | grep sqlalchemy
: 1598149936:0;pip3 install sqlalchemy
: 1598151249:0;cd sqlalchemy
: 1598151249:0;ls
: 1598151256:0;python3 app.py
: 1598151575:0;python3 app.py main
: 1598151582:0;python3 main
: 1598152244:0;python3 app.py
: 1598152247:0;./app.py
: 1598155212:0;cd test-package
: 1598155213:0;ls
: 1598155224:0;python
: 1598155482:0;python3
: 1598157460:0;python
: 1598157569:0;python3
: 1598157945:0;cd ..
: 1598157947:0;cd sqlalchemy-demo
: 1598157948:0;ls
: 1598158504:0;python3
: 1598159377:0;ls
: 1598159381:0;python3 db.py
: 1598159398:0;import db.py
: 1598159407:0;import db
: 1598170947:0;docker ps
: 1598171058:0;docker pull mysql/mysql-server:lastest
: 1598171075:0;docker pull mysql/mysql-server:latest
: 1598171155:0;docker run --name mysql -d mysql/mysql-server:latest
: 1598171179:0;docker ps -a
: 1598171193:0;docker rm d641fdb52a61
: 1598171196:0;docker ps -a
: 1598171201:0;docker run --name mysql -d mysql/mysql-server:latest
: 1598171206:0;docker ps
: 1598171245:0;docker exec -it 8026103f932a bash
: 1598171453:0;docker exec -it mysql1 mysql -uroot -p'
: 1598171455:0;docker exec -it mysql1 mysql -uroot -p
: 1598171463:0;docker exec -it mysql mysql -uroot -p
: 1598171613:0;docker-compose up -d
: 1598171619:0;docker ps
: 1598171712:0;pip3 install clickhouse_sqlalchemy
: 1598171906:0;clear
: 1598237382:0;docker-compose up -d
: 1598237611:0;cd ..
: 1598237624:0;docker ps
: 1598237639:0;docker exect -it 767b60f7610e
: 1598237645:0;docker exec -it 767b60f7610e
: 1598237659:0;docker exec -it 767b60f7610e /bin/bash
: 1598237995:0;git status
: 1598238007:0;git checkout master
: 1598238017:0;git pull origin master
: 1598238161:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598239204:0;git status
: 1598239249:0;git checkout -b user_segments_update
: 1598239263:0;git branch
: 1598239278:0;git merge user_segments_update
: 1598239287:0;git status
: 1598239350:0;git merge users_segments_update
: 1598239376:0;git rm -D users_segments_update
: 1598239392:0;git branch -R users_segments_update
: 1598239417:0;git branch -D users_segments_update
: 1598239421:0;git status
: 1598244553:0;faust -A app --debug worker -l info
: 1598245286:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083390"}'
: 1598245329:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a2", "at":"1598083480"}'
: 1598245369:0;docker-compose up -d
: 1598245400:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598247006:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083390"}'
: 1598247062:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598247071:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083390"}'
: 1598248764:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598248795:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083390"}'
: 1598248973:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598248977:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083390"}'
: 1598249083:0;pip3 install .
: 1598249088:0;cd ..
: 1598249100:0;pip3 install .
: 1598249113:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598249121:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083390"}'
: 1598249262:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598249267:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598083390"}'
: 1598249349:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"11", "state": "out", "user":"a1", "at":"1598083390"}'
: 1598249409:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s11", "state": "out", "user":"a1", "at":"1598083390"}'
: 1598249444:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s10", "state": "out", "user":"a1", "at":"1598083390"}'
: 1598249448:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a1", "at":"1598083480"}'
: 1598249573:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a2", "at":"1598083480"}'
: 1598249691:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598249717:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"user1", "at":"1598083560"}'
: 1598249755:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"user2", "at":"1598083560"}'
: 1598250482:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085000"}'
: 1598250513:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a2", "at":"1598085001"}'
: 1598250533:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a3", "at":"1598085002"}'
: 1598250541:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "in", "user":"a1", "at":"1598085003"}'
: 1598250546:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "in", "user":"a2", "at":"1598085004"}'
: 1598250946:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s3", "state": "in", "user":"a1", "at":"1598085005"}'
: 1598258231:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598262836:0;git status
: 1598262896:0;git add prile/.
: 1598262929:0;git commit -m 'user-segments update api and stream'
: 1598262938:0;git push origin user_segments_update
: 1598263281:0;git fetch
: 1598263324:0;git checkout master
: 1598263330:0;git pull origin master
: 1598263341:0;git checkout user_segments_update
: 1598263346:0;git merge master
: 1598263359:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598263438:0;pip3 install -r requirements.txt
: 1598263522:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598268697:0;git status
: 1598268706:0;git add prile/.
: 1598268785:0;git commit -m 'get profile brief api'
: 1598268795:0;git push origin user_segments_update
: 1598268804:0;git status
: 1598271587:0;git add prile/.
: 1598271592:0;git commit -m 
: 1598271614:0;git commit -m 'added limit for get profile query'
: 1598271656:0;git status
: 1598271670:0;git add prile/.
: 1598271699:0;git commit -m 'edit path get profile brief api'
: 1598271709:0;git push origin user_segments_update
: 1598271854:0;git checkout -b hotfix-response-dto
: 1598279649:0;git status
: 1598281468:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598281475:0;docker-compose up -d
: 1598281486:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598282854:0;git status
: 1598322033:0;git log
: 1598322091:0;git reset --hard
: 1598322103:0;git status
: 1598322623:0;git checkout master
: 1598322634:0;git pull origin master
: 1598322648:0;docker-compose up -d
: 1598324472:0;git branch -D fix_identity_schema
: 1598324474:0;git branch
: 1598324488:0;git branch -D test-faust
: 1598324506:0;git branch -D segment_agg_final_v
: 1598324518:0;git branch -D hotfix-response-dto
: 1598324579:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598325740:0;sudo snap install postman
: 1598326349:0;git status
: 1598326683:0;git checkout -b refactor_segment_report
: 1598336535:0;git status
: 1598337371:0;git commit -m 'refacting...i have switch to get total user per source'
: 1598337381:0;git checkout master
: 1598337385:0;git status
: 1598337395:0;git commit -am 'refacting...i have switch to get total user per source'
: 1598337399:0;git checkout master
: 1598337401:0;git status
: 1598337524:0;docker ps
: 1598337541:0;docker exec -it 767b60f7610e /bin/bash
: 1598352549:0;git checkout -b agg_by_source
: 1598356855:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598368864:0;postman
: 1598368877:0;sudo postman
: 1598398958:0;docker compose up -d
: 1598398996:0;docker-compose up -d
: 1598399019:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598406405:0;docker ps
: 1598406413:0;docker exec -it 767b60f7610e /bin/bash
: 1598421641:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598426857:0;git status
: 1598426874:0;git add prile/.
: 1598426978:0;git commit -m "done 3 api total user, with ts, total event name, copy sql into database, refactor'\
"
: 1598430810:0;git status
: 1598430922:0;git push origin agg_by_source
: 1598454218:0;adf
: 1598454220:0;clear
: 1598454221:0;docker ps
: 1598454245:0;docker-compose up -d
: 1598454254:0;docker ps
: 1598455993:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598456280:0;git status
: 1598456297:0;git stash
: 1598456299:0;git status
: 1598456302:0;git checkout master
: 1598456305:0;git status
: 1598456315:0;git pull origin master
: 1598456338:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598493003:0;clear
: 1598493138:0;docker-compose up -d
: 1598493166:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598493245:0;git status
: 1598493253:0;git checkout -b total-user
: 1598493832:0;docker ps
: 1598493838:0;clear
: 1598493851:0;docker exec -it 767b60f7610e /bin/bash
: 1598500092:0;git status
: 1598500099:0;git add prile/.
: 1598500233:0;git commit -m 'confuse should separate with get segment report agg'
: 1598500265:0;git branch refactor_segment_report
: 1598500312:0;git checkout  refactor_segment_report
: 1598500541:0;git checkout total-user
: 1598506612:0;clear
: 1598506613:0;git status
: 1598506645:0;git add prile/.
: 1598506772:0;git commit -m 'total user by segment api, tested'
: 1598506904:0;git commit -am 'edited name for api'
: 1598507247:0;git checkout master
: 1598507253:0;git pull origin master
: 1598509652:0;docker ps
: 1598527363:0;telnet 20.10.23.65 22
: 1598527370:0;telnet 20.10.23.165 22
: 1598527384:0;telnet 20.10.23.165 9000
: 1598537394:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598539507:0;git status
: 1598539723:0;git checkout -b switch_view_to_execute_native
: 1598544972:0;git checkout -b test-
: 1598544979:0;git status
: 1598545076:0;git add .
: 1598545106:0;git commit -m 'fix import file and some name class'
: 1598545108:0;git status
: 1598572676:0;git branch -m --help
: 1598572684:0;git branch --help
: 1598572714:0;git branch -m change_import_file
: 1598572716:0;git status
: 1598572718:0;clear
: 1598573460:0;git checkout master
: 1598573467:0;git pull origin master
: 1598573582:0;git fetch
: 1598573717:0;git status
: 1598576916:0;git merge change_import_file
: 1598578675:0;git status
: 1598580088:0;docker-compose up -d
: 1598580378:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598581405:0;git merge refactor_segment_report
: 1598581460:0;git commit -m 'merged with hot-fix naming'
: 1598581462:0;git status
: 1598581483:0;git commit -am 'merged with hot-fix naming'
: 1598581492:0;git merge refactor_segment_report
: 1598582474:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598583291:0;docker ps
: 1598583309:0;docker exec -it 767b60f7610e /bin/bash
: 1598584613:0;git status
: 1598584639:0;git commit -m 'merged with refactor segment report'
: 1598584641:0;git status
: 1598584668:0;git commit -am 'merged with refactor segment report'
: 1598584672:0;git status
: 1598585935:0;git push origin master
: 1598586086:0;git branch
: 1598586235:0;git checkout -b add_tests
: 1598588555:0;git status
: 1598588573:0;git add tests/http/persistance/test_segment_final.py
: 1598588575:0;git status
: 1598588618:0;git commit -m 'added test simple segment_final performace'
: 1598588629:0;git checkout master
: 1598588644:0;git merge add_tests
: 1598588898:0;git checkout -b total_user_by_segment_ts
: 1598589993:0;docker ps
: 1598590001:0;docker exec -it 767b60f7610e /bin/bash
: 1598598740:0;docker-compose up -d
: 1598599061:0;docker ps
: 1598599081:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598599634:0;docker ps
: 1598599645:0;docker exec -it 767b60f7610e /bin/bash
: 1598600328:0;git status
: 1598600343:0;git add prile/.
: 1598600374:0;git commit -m 'done get total user by segment time series'
: 1598600580:0;git checkout -b learn_more_fast_api
: 1598600943:0;git checkout total_user_by_segment_ts
: 1598600960:0;git push origin total_user_by_segment_ts
: 1598601384:0;git status
: 1598601393:0;git checkout  learn_more_fast_api
: 1598601395:0;git status
: 1598606814:0;docker-compose up -d
: 1598606821:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598664879:0;docker-compose up -d
: 1598664886:0;docker ps
: 1598664910:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598664953:0;git checkout master
: 1598664962:0;git pull origin master
: 1598664989:0;git checkout learn_more_fast_api
: 1598665019:0;git checkout -b validation-request
: 1598668302:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598688884:0;git branch
: 1598688908:0;git status
: 1598688932:0;git branch -help
: 1598688980:0;git branch -M refactor_request_parameter
: 1598688986:0;git status
: 1598688992:0;git add prile/.
: 1598689016:0;git commit -m 'change request parameter fast api'
: 1598689019:0;git status
: 1598689033:0;git push origin refactor_request_parameter
: 1598689327:0;git checkout master
: 1598689391:0;git checkout origin/refactor_request_parameter
: 1598689404:0;git fetch origin refactor_request_parameter
: 1598689440:0;git branch
: 1598689489:0;git checkout refactor_request_parameter
: 1598689540:0;git status
: 1598689550:0;git add prile/.
: 1598689554:0;git status
: 1598689576:0;git commit -m 'deleted file test fastapi'
: 1598689585:0;git push origin refactor_request_parameter
: 1598689601:0;git checkout origin/refactor_request_parameter
: 1598689673:0;git fetch origin refactor_request_parameter
: 1598689736:0;git checkout master
: 1598689806:0;git merge origin refactor_request_parameter 
: 1598689845:0;git push orign master
: 1598689854:0;git push origin master
: 1598689879:0;git status
: 1598690136:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598690381:0;git pull origin master
: 1598691294:0;git status
: 1598691302:0;git add prile/.
: 1598691306:0;git status
: 1598691357:0;git commit -m 'update sql rename segments to segment_users and users to user_segments'
: 1598691362:0;git push origin master
: 1598691514:0;git branch learn_more_fast_api
: 1598691532:0;git checkout learn_more_fast_api
: 1598691656:0;git merge master
: 1598692107:0;clear
: 1598692114:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598692827:0;git status
: 1598692838:0;git add prile/.
: 1598692985:0;git commit -m "parameters filter replace List to Set, prevent duplicate input"
: 1598753517:0;docker-compose up -d
: 1598753525:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598760783:0;git status
: 1598760796:0;git add prile/.
: 1598760863:0;git commit -m "handing some exceptions http"
: 1598760904:0;git add prile/.
: 1598760931:0;git commit -m "remove lines debug"
: 1598777853:0;cd ..
: 1598777853:0;ls
: 1598777862:0;cd python-course
: 1598777863:0;ls
: 1598799376:0;docker-compose up -d
: 1598799382:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598845778:0;git status
: 1598845800:0;git add prile/.
: 1598845802:0;git status
: 1598845891:0;git commit -m "trying dependency params..."
: 1598845899:0;git checkout master
: 1598845930:0;git checkout learn_more_fast_api
: 1598845933:0;git log
: 1598845986:0;git checkout -b add_exceptions
: 1598845999:0;git push origin add_exceptions
: 1598846153:0;git checkout master
: 1598846161:0;git fetch
: 1598846288:0;git merge origin origin add_exceptions
: 1598846303:0;git push origin master
: 1598846334:0;git checkout test
: 1598846344:0;git checkout -b test
: 1598846355:0;	docker-compose up -d
: 1598846472:0;docker ps
: 1598846532:0;docker exec -it 767b60f7610e /bin/bash
: 1598846879:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598847629:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085000"}'
: 1598847853:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085001"}'
: 1598847873:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598847880:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085002"}'
: 1598848024:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a1", "at":"1598085010"}'
: 1598848050:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "out", "user":"a1", "at":"1598085010"}'
: 1598848089:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s3", "state": "out", "user":"a1", "at":"1598085010"}'
: 1598848148:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a2", "at":"1598085010"}'
: 1598848169:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a3", "at":"1598085010"}'
: 1598848194:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "out", "user":"a2", "at":"1598085010"}'
: 1598848238:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "out", "user":"a3", "at":"1598085020"}'
: 1598848618:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085000"}'
: 1598848914:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a2", "at":"1598085001"}'
: 1598849246:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "in", "user":"a1", "at":"1598085005"}'
: 1598849340:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "in", "user":"a3", "at":"1598085010"}'
: 1598849488:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085020"}'
: 1598849573:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a1", "at":"1598085020"}'
: 1598849598:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a1", "at":"1598085021"}'
: 1598851820:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a10", "at":"1598085031"}'
: 1598852097:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a10", "at":"1598085040"}'
: 1598852198:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598852380:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s11", "state": "in", "user":"a11", "at":"1598085040"}'
: 1598852693:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s11", "state": "out", "user":"a11", "at":"1598085038"}'
: 1598853018:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s11", "state": "in", "user":"a12", "at":"1598085040"}'
: 1598855049:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598855110:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s11", "state": "in", "user":"a13", "at":"1598085040"}'
: 1598855186:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s11", "state": "out", "user":"a14", "at":"1598085042"}'
: 1598855501:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598855526:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":2, "segment":"s11", "state": "out", "user":"a15", "at":"1598085045"}'
: 1598856060:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "in", "user":"a1", "at":"1598085050"}'
: 1598856215:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "out", "user":"a1", "at":"1598085049"}'
: 1598856390:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598856412:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "out", "user":"a1", "at":"1598085045"}'
: 1598856821:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598856875:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "in", "user":"a2", "at":"1598085050"}'
: 1598857100:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598857115:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "in", "user":"a3", "at":"1598085050"}'
: 1598857451:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "out", "user":"a3", "at":"1598085048"}'
: 1598857720:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598857737:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "out", "user":"a3", "at":"1598085047"}'
: 1598857877:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":3, "segment":"s1", "state": "out", "user":"a3", "at":"1598085046"}'
: 1598857881:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598860447:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085100"}'
: 1598860853:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s1", "state": "in", "user":"a1", "at":"1598085100"}'
: 1598860867:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598860905:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s1", "state": "in", "user":"a2", "at":"1598085101"}'
: 1598860943:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s1", "state": "out", "user":"a1", "at":"1598085102"}'
: 1598861590:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s1", "state": "out", "user":"a2", "at":"1598085120"}'
: 1598861662:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s1", "state": "in", "user":"a3", "at":"1598085150"}'
: 1598861666:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":5, "segment":"s1", "state": "in", "user":"a4", "at":"1598085151"}'
: 1598862820:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598862890:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085200"}'
: 1598862930:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a2", "at":"1598085201"}'
: 1598862992:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "out", "user":"a1", "at":"1598085202"}'
: 1598863031:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085203"}'
: 1598864024:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598864812:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "user_id":"user1", "anonymous_id": "a1", "identities":[], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598864864:0;faust -A prile.workflows.profile_update.app send "profile_updated"  '{"tenant_id":1, "user_id":"user1", "anonymous_id": "a1", "identities":[], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598864887:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "user_id":"user1", "anonymous_id": "a1", "identities":[], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598867430:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598867436:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "user_id":"user1", "anonymous_id": "a1", "identities":[], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598869633:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598869640:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "user_id":"user1", "anonymous_id": "a1", "identities":[], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598869769:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "user_id":"user1", "anonymous_id": "a1", "identities":[], "str_prfaust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1,' ||operties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598869784:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870081:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870097:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870135:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870165:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870516:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870522:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870621:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870626:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870692:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870698:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870730:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870733:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870776:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870779:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870803:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870835:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598870906:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598870911:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598871258:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598871262:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598871483:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598871486:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598871920:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598871925:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598871965:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598871968:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598872131:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598872134:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598872237:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598872240:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598872613:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598872616:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598873365:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598873910:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598873964:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598873967:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598874263:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598874266:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598874348:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598874351:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598874405:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598874409:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598874554:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598874557:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598874884:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598874887:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598875019:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598875022:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598875380:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598875383:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598875684:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598875688:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598875725:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598875732:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598875913:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598875917:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876121:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598876125:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876159:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598876162:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876259:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598876262:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876293:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598876296:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876540:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598876543:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876578:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598876581:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876768:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598876773:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598876836:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s3", "state": "in", "user":"a1", "at":"1598085005"}'
: 1598876844:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598876944:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1598876974:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598877629:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598877638:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1598877645:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598878076:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598878080:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1598878084:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598878235:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598878239:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598878605:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598878608:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1598878611:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598878636:0;git status
: 1598878644:0;git add prile/.
: 1598878654:0;git commit -m 'fix convertion event'
: 1598878661:0;git push origin test
: 1598888059:0;	docker-compose up -d
: 1598888186:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598888201:0;	docker-compose up -d
: 1598888204:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598888240:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598892912:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598925938:0;git status
: 1598925972:0;docker exec -it 767b60f7610e /bin/bash
: 1598925978:0;	docker-compose up -d
: 1598926014:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598926032:0;	docker-compose up -d
: 1598926045:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598926096:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598926501:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598926524:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598926658:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598926663:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598926672:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598926883:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598926930:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598926932:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598926979:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598927088:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598927106:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a1", "event_name": "View", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598927160:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598927224:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598927349:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598927351:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598927435:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598927438:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598927630:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598928089:0;docker ps
: 1598928099:0;docker exec -it 767b60f7610e /bin/bash
: 1598928156:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598928170:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598928233:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598928236:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598929354:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598929359:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598929454:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598929561:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598930155:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598930178:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598930427:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598930433:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598930435:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598930607:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598930609:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598930805:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598930808:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598931041:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598931045:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598931265:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598931271:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598931411:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598931413:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["levanchi"], "identity_vals" : ["user_id"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1598931634:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[24],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085500}'
: 1598931903:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598932194:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598932197:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598932200:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598932364:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598932813:0;git status
: 1598932827:0;git add prile/.
: 1598932859:0;git commit -m "fixed conversion broadcast run full flow"
: 1598933055:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598934338:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934190"}'
: 1598934441:0;faust -A prile.workflows.profile_update.app worker -l info -p
: 1598934457:0;faust -A prile.workflows.profile_update.app worker -l info
: 1598934484:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1598934499:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598934527:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934190"}'
: 1598934652:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1598934695:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934190"}'
: 1598934709:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934191"}'
: 1598934836:0;CREATE MATERIALIZED VIEW segment_agg_gender_mv TO segment_agg AS
: 1598934836:0;SELECT
: 1598934836:0;FROM
: 1598934836:0;(\
    SELECT\
        sf.tenant_id,\
        sf.segment_id,\
        pf.cate,\
        count() AS count\
    FROM\
    (\
        SELECT\
            tenant_id,\
            segment_id,\
            users\
        FROM\
        (\
            SELECT\
                tenant_id,\
                segment_id,\
                argMaxMerge(users) AS users\
            FROM segment_users_final\
            GROUP BY\
                tenant_id,\
                segment_id\
        )\
        ARRAY JOIN users\
    ) AS sf
: 1598934837:0;GROUP BY
: 1598934837:0;;
: 1598934881:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934191"}'
: 1598934896:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934192"}'
: 1598936404:0;git status
: 1598936409:0;git add prile/.
: 1598936434:0;git commit -m "tested and fix some bugs apis"
: 1598936441:0;git push orgin test
: 1598936456:0;git status
: 1598936461:0;git push origin test
: 1598941104:0;cd ..
: 1598941112:0;git clone git@github.com:dls-controls/python-logging-configuration.git
: 1598941137:0;ls
: 1598941141:0;cd python-course
: 1598941142:0;cd ..
: 1598941148:0;cd python-logging-configuration
: 1598944501:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598947070:0;git status
: 1598947082:0;git add prile/.
: 1598947109:0;git commit -m "remove debug lines"
: 1598947114:0;git push origin test
: 1598949062:0;git add prile/.
: 1598949073:0;git commit -m "remove debug lines"
: 1598949077:0;git push origin test
: 1598949087:0;git checkout master
: 1598949093:0;git merge test
: 1598949100:0;git push origin master
: 1598951077:0;clear
: 1598951090:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598951097:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598951502:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598951504:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598951519:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598951644:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p
: 1598951650:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1598951761:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598951774:0;docker ps
: 1598951780:0;	docker-compose up -d
: 1598952081:0;git pull origin master
: 1598952148:0;git status
: 1598952154:0;git add prile/.
: 1598952166:0;git commit -m 'delete recommen entity'
: 1598952171:0;git push origin master
: 1598952183:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598952274:0;pip3 install -r requirements.txt
: 1598952332:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598952555:0;cd ..
: 1598952558:0;ls
: 1598952582:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598953193:0;git pull master
: 1598953197:0;git pull origin master
: 1598953209:0;git status
: 1598953212:0;git stash
: 1598953216:0;git pull origin master
: 1598953251:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598953375:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598953515:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598953521:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598953617:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598953775:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598953779:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598953862:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1598954238:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598954241:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598954352:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598954356:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598956909:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6067
: 1598956998:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1598957646:0;clear
: 1598957713:0;pip3 install .
: 1598957729:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598957850:0;pip3 install .
: 1598957858:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1598958015:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599055237:0;ifconfig
: 1599055253:0;clear
: 1599055255:0;ifconfig
: 1599058123:0;clear
: 1599058210:0;docker-compose up -d
: 1599058345:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599058356:0;docker-compose up -d
: 1599058359:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599058434:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599058701:0;docker ps
: 1599058730:0;docker exec -it a2b0f45e64ea bash
: 1599098695:0;docker-compose up -d
: 1599098755:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599098761:0;docker-compose up -d
: 1599098780:0;docker ps
: 1599098786:0;docker exec -it a2b0f45e64ea bash
: 1599099241:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599099252:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599099257:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599099544:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599099547:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599103552:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599103555:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599103624:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599103627:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599103648:0;docker-compose up -d
: 1599103651:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599103663:0;clear
: 1599103982:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599104298:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599104571:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599104591:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599104594:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599104700:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599104703:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599104730:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599104732:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599104770:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599104863:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599104889:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599104891:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599104968:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599104973:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599105001:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599105004:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599105145:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599105147:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599105209:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599105212:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599109328:0;docker ps
: 1599109337:0;docker exec -it 767b60f7610e /bin/bash
: 1599109805:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599109810:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599110038:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599110040:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599110403:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599110380'
: 1599110455:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599110380}'
: 1599110488:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599110507:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599110538:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599110645:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599110655:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599110723:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599110726:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599110817:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599110820:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599110842:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599110380}'
: 1599110880:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599110868}'
: 1599113280:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113268}'
: 1599113496:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599113511:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113268}'
: 1599113515:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113269}'
: 1599113518:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113270}'
: 1599113522:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113271}'
: 1599113525:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113272}'
: 1599113528:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[6],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113273}'
: 1599113531:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[7],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113274}'
: 1599113534:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[8],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113275}'
: 1599113537:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[9],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113276}'
: 1599113540:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599115353:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599115394:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{ "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113278}'
: 1599115484:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599115486:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{ "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113278}'
: 1599115522:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599115531:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{ "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113278}'
: 1599115600:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113278}'
: 1599115622:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599115627:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113278}'
: 1599115697:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599115720:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113278}'
: 1599115830:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{ "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113278}'
: 1599118321:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599118325:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113268}'
: 1599118331:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113269}'
: 1599118334:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113270}'
: 1599118338:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113271}'
: 1599118342:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113272}'
: 1599118345:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[6],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113273}'
: 1599118496:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[7],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113274}'
: 1599118501:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c2"],"num_properties_keys":["total_value"],"num_properties_vals":[8],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113275}'
: 1599118504:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[9],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113276}'
: 1599118508:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599118890:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599118896:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599119304:0;git status
: 1599119316:0;git add prile/
: 1599119374:0;git commit -m "campaign total revenue"
: 1599119528:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599119533:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113274}'
: 1599119536:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113275}'
: 1599119540:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113276}'
: 1599119543:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599125117:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599127068:0;pip3 install loguru
: 1599127418:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599127769:0;pip3 install loguru
: 1599129662:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599129726:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599130303:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599130305:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599130378:0;clear
: 1599130378:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599130395:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599130420:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599130423:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599130434:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599130438:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599130520:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599130524:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599130679:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599130691:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599130715:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599130726:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599130787:0;docker ps
: 1599130797:0;docker-compose up -d
: 1599130820:0;clear
: 1599130824:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599130838:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599130975:0;pip3 install .
: 1599130987:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599130994:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599131149:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599131160:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599131213:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599131219:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599131635:0;git status
: 1599131641:0;git add prile/.
: 1599131676:0;git commit -m "change logging to loguru"
: 1599140563:0;dpkg --list
: 1599140590:0;dpkg --list | grep audio
: 1599140669:0;sudo apt-get purge audio-recorder && sudo apt-get autoremove
: 1599141110:0;cd ..
: 1599141111:0;ls
: 1599141127:0;sudo pip install pinject
: 1599141502:0;pip3 install pinject
: 1599141520:0;which pip
: 1599141527:0;which pip3
: 1599141595:0;pip3 frezee
: 1599141602:0;pip3 freeze
: 1599141715:0;python3
: 1599141786:0;sudo pip3 install pinject
: 1599141938:0;which pip3
: 1599142506:0;pls
: 1599142507:0;ls
: 1599142511:0;cd .python3
: 1599142512:0;ls
: 1599142515:0;cd bin
: 1599142517:0;./activate
: 1599142522:0;sudo ./activate
: 1599142529:0;sudo /activate
: 1599142571:0;which pip3
: 1599142609:0;pip3 freeze
: 1599142620:0;pip3 install pinject
: 1599185329:0;git status
: 1599185364:0;git add requirements.txt
: 1599185401:0;git commit -m "add loguru to requirement txt"
: 1599185405:0;git status
: 1599185424:0;git checkout -b develop
: 1599185462:0;git push origin develop
: 1599186224:0;python3
: 1599186927:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599186941:0;docker-compose up -d
: 1599186949:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599187199:0;git status
: 1599187327:0;git add prile/.
: 1599187347:0;git commit -m "change post to get to deploy"
: 1599187351:0;git push origin develop
: 1599191511:0;pip3 install loguru
: 1599205263:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599205280:0;docker-compose up -d
: 1599205289:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599205409:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599205553:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599205615:0;docker ps
: 1599205625:0;docker exec -it a2b0f45e64ea bash
: 1599206365:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599206370:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599206439:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599206441:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599206542:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599206545:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599206804:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599206806:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599206858:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1599206861:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599206907:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113280}'
: 1599206936:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":3, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113280}'
: 1599206991:0;git status
: 1599207087:0;git add prile/. 
: 1599207146:0;git commit -m "rename increasing_amount to delta_amount, use incr_by_float of redis"
: 1599207150:0;git push origin develop
: 1599208210:0;git status
: 1599208215:0;git add prile/.
: 1599208389:0;git commit -m "add strong type before go into redis"
: 1599208394:0;git push origin develop
: 1599210321:0;git config --global alias.a "add"
: 1599210339:0;git status
: 1599210370:0;git status -s
: 1599210382:0;git status
: 1599210478:0;git status -s
: 1599210672:0;git config --global alias.s "status -s"
: 1599210675:0;git s
: 1599210728:0;git add . --help
: 1599210833:0;git commit --helop
: 1599210837:0;git commit --help
: 1599210942:0;git config --global alias.br "branch"
: 1599210969:0;git config --global alias.cm "commit -m"
: 1599210990:0;git cm "add play feature"
: 1599210993:0;git s
: 1599211000:0;git status
: 1599211021:0;git s
: 1599211045:0;git status
: 1599211083:0;git s
: 1599211085:0;git status
: 1599211112:0;ls
: 1599211126:0;git cm "git alias"
: 1599211141:0;git diff
: 1599211197:0;git config --global alias.co "checkout"
: 1599211229:0;git config --global alias.cob "checkout -b"
: 1599211268:0;git config --global alias.log "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
: 1599211269:0;git log
: 1599211305:0;git config --global alias.tree "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
: 1599211308:0;git tree
: 1599211338:0;git log
: 1599211342:0;git tree
: 1599211351:0;git yolo
: 1599211360:0;git co master
: 1599211365:0;git co develop
: 1599211369:0;git s
: 1599211373:0;git status
: 1599211390:0;git s
: 1599211431:0;git br
: 1599211482:0;git config --global alias.tree "log --graph --topo-order --abbrev-commit --date=short --decorate --all --boundary --pretty=format:'%Cgreen%ad %Cred%h%Creset -%C(yellow)%d%Creset %s %Cblue[%cn]%Creset %Cblue%G?%Creset'"
: 1599211484:0;git tree
: 1599211534:0;git diff --check --dirstat --find-copies --find-renames --histogram --color
: 1599211542:0;git status
: 1599211547:0;git diff
: 1599211556:0;git diff --check --dirstat --find-copies --find-renames --histogram --color
: 1599211909:0;git push --help
: 1599212024:0;git s
: 1599212025:0;git cm
: 1599212036:0;git s
: 1599212062:0;git branch -a
: 1599212070:0;git branch
: 1599212073:0;git br
: 1599212082:0;git branch -a
: 1599212085:0;git br
: 1599212094:0;git stash list
: 1599212295:0;git tree
: 1599212384:0;git stash list
: 1599212433:0;git s
: 1599212507:0;git 
: 1599212508:0;git s
: 1599212510:0;clear
: 1599212511:0;git s
: 1599212526:0;git a .
: 1599212528:0;git s
: 1599212533:0;git status
: 1599212540:0;git add .
: 1599212542:0;git status
: 1599212554:0;git cm "add file 3"
: 1599212557:0;git s
: 1599212634:0;git stash save "toi dang lam feature dang_do va can quay lai de hotfix"
: 1599212663:0;git s
: 1599212665:0;git status
: 1599212671:0;git tree
: 1599212715:0;git stash save --help
: 1599212876:0;git tree
: 1599212924:0;git stash list
: 1599213048:0;git s
: 1599213387:0;git status
: 1599213389:0;git s
: 1599213407:0;git cob develop
: 1599213427:0;git co master
: 1599213447:0;git s
: 1599213457:0;git co develop
: 1599213464:0;git s
: 1599213470:0;git co master
: 1599213483:0;git a .
: 1599213485:0;git s
: 1599213498:0;git co develop
: 1599213533:0;git tree
: 1599213541:0;git co master
: 1599213568:0;git stash "doing... in file 4"
: 1599213581:0;git stash  save "doing... in file 4"
: 1599213584:0;git stash list
: 1599213594:0;git tree
: 1599213652:0;git stash list
: 1599213661:0;git ls
: 1599213664:0;clear
: 1599213671:0;git tree
: 1599213828:0;git s
: 1599213832:0;git a .
: 1599213846:0;git cm "forever"
: 1599213848:0;git s
: 1599213925:0;git stash save --help
: 1599213999:0;git s
: 1599214003:0;git tree
: 1599214021:0;git stash list
: 1599214077:0;git tree
: 1599214125:0;git stash list
: 1599214266:0;git stash show 
: 1599214285:0;git stash show -p
: 1599214353:0;git stash list
: 1599214360:0;git stash show 
: 1599214375:0;git tree
: 1599214402:0;git stash list
: 1599214413:0;git stash list --help
: 1599214443:0;git stash list -p
: 1599214473:0;git stash pop 
: 1599214494:0;git s
: 1599214510:0;git tree
: 1599214525:0;git stash list
: 1599214530:0;git tree
: 1599214574:0;git s
: 1599214582:0;git a file4.txt validation_info.txt
: 1599214583:0;git s
: 1599214610:0;git cm "xong viec roi nha"
: 1599214611:0;git s
: 1599214614:0;git stash list
: 1599214619:0;git tree
: 1599214650:0;git stash list
: 1599214664:0;git stash pop stash@{0}
: 1599214691:0;git s
: 1599214701:0;git cm "done feature dang_do"
: 1599214703:0;git s
: 1599214710:0;git add file3.txt
: 1599214720:0;git cm "done feature dang do"
: 1599214725:0;git s
: 1599214729:0;git tree
: 1599214813:0;git s
: 1599214838:0;git stash save -u "toi vua add file chua dc track"
: 1599214855:0;git stash list
: 1599214861:0;git stash pop
: 1599214878:0;git s
: 1599214919:0;git a file_tracked.py
: 1599214920:0;git s
: 1599214938:0;git stash save "tam luu lai do"
: 1599214956:0;git s
: 1599214967:0;git stash save --help
: 1599215000:0;git stash save -u "tam cat lai untracked file"
: 1599215007:0;git stash list
: 1599215061:0;git s
: 1599215111:0;git stash save -u "cat chuyen yeu duong lai"
: 1599215114:0;git stash list
: 1599215139:0;git s
: 1599215143:0;git add file2.txt
: 1599215149:0;git a file2
: 1599215160:0;git cm "try stash conflic"
: 1599215161:0;git s
: 1599215165:0;git tree
: 1599215185:0;git stash show
: 1599215310:0;git stash apply 
: 1599215380:0;git s
: 1599215387:0;git status
: 1599215404:0;git cm "final : tho yeu tho trc da nha"
: 1599215405:0;git s
: 1599215407:0;git tree
: 1599215421:0;git stash list
: 1599215447:0;git stash drop 
: 1599215450:0;git stash list
: 1599215458:0;git stash pop
: 1599215464:0;git s
: 1599215477:0;git add untrack_file.txt
: 1599215478:0;git s
: 1599215497:0;git cm "tested stash track and untrack file"
: 1599215502:0;git tree
: 1599215674:0;clear
: 1599216563:0;git stash list
: 1599216573:0;git stash clear
: 1599216576:0;git stash list
: 1599216578:0;git tree
: 1599216670:0;git co origin develop
: 1599216798:0;git s
: 1599216813:0;git tree
: 1599216851:0;git cm master
: 1599216856:0;git co master
: 1599216906:0;git br
: 1599216919:0;git fetch origin develop
: 1599216936:0;git co origin/develop
: 1599216944:0;git tree
: 1599216976:0;git co master
: 1599217007:0;git tree
: 1599217156:0;git merge develop
: 1599217159:0;git tree
: 1599217470:0;git push origin master
: 1599217479:0;git tree
: 1599218273:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599232346:0;docker-compose up -d
: 1599232353:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599232366:0;docker-compose up -d
: 1599232373:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599232627:0;git s
: 1599234307:0;pip3 install sqlalchemy
: 1599234324:0;pip3 install clickhouse_sqlalchemy
: 1599234446:0;docker ps
: 1599234468:0;docker exec -it 767b60f7610e /bin/bash
: 1599280673:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599299739:0;git status
: 1599299806:0;git stash save "try session with..."
: 1599299842:0;git cob fix_session_with
: 1599300317:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599300803:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599300947:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598085000"}'
: 1599300962:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598086000"}'
: 1599300985:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934193"}'
: 1599301055:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599301059:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934193"}'
: 1599301067:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1598934194"}'
: 1599301758:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599302588:0;git s
: 1599302625:0;git cm "now can use with session"
: 1599302638:0;git push origin fix_session_with
: 1599302753:0;git s
: 1599302761:0;git tree
: 1599302775:0;git add prile/.
: 1599302776:0;git s
: 1599302788:0;git cm "now can use with session"
: 1599302796:0;git push origin fix_session_with
: 1599314984:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599314989:0;clear
: 1599315063:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599315072:0;docker-compose up -d
: 1599315078:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599315091:0;docker-compose up -d
: 1599320104:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320066"}'
: 1599320153:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599320157:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320066"}'
: 1599320200:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320067"}'
: 1599320796:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599320808:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320068"}'
: 1599320913:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599320918:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320069"}'
: 1599321195:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599321213:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320070"}'
: 1599321217:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a2", "at":"1599320071"}'
: 1599321221:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "out", "user":"a1", "at":"1599320072"}'
: 1599321225:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a2", "at":"1599320073"}'
: 1599321228:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a3", "at":"1599320074"}'
: 1599321231:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a4", "at":"1599320075"}'
: 1599321235:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a5", "at":"1599320076"}'
: 1599321238:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a6", "at":"1599320077"}'
: 1599321240:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s2", "state": "in", "user":"a1", "at":"1599320078"}'
: 1599321244:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s2", "state": "in", "user":"a2", "at":"1599320079"}'
: 1599321247:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s2", "state": "in", "user":"a3", "at":"1599320080"}'
: 1599321250:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s2", "state": "in", "user":"a4", "at":"1599320081"}'
: 1599321253:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s2", "state": "in", "user":"a5", "at":"1599320082"}'
: 1599321257:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s2", "state": "in", "user":"a6", "at":"1599320083"}'
: 1599321595:0;git s
: 1599321605:0;git a prile/.
: 1599321607:0;git s
: 1599321635:0;git cm "support async for users segments update"
: 1599321637:0;git s
: 1599321644:0;git push origin fix_session_with
: 1599384400:0;sudo snap install exercism
: 1599384418:0;ls
: 1599384422:0;cd exercism
: 1599384423:0;ls
: 1599384425:0;exercism download --exercise=hello-world --track=python
: 1599384552:0;exercism version
: 1599384608:0;exercism configure --token=838e1f92-570d-496c-adc5-a16745b5abb8
: 1599384656:0;838e1f92-570d-496c-adc5-a16745b5abb8
: 1599384660:0;exercism download --exercise=hello-world --track=python
: 1599384820:0;ln -s /home/chile/snap/exercism/5/exercism/ /home/chile/PycharmProjects/Github/MyProjects/python/exercism
: 1599384865:0;clear
: 1599385161:0;ls
: 1599385165:0;cd exercism
: 1599385173:0;cd python/hello-world
: 1599385174:0;ls
: 1599385215:0;pytest -m hello_world_test.py
: 1599385521:0;python -m pytest hello_world_test.py
: 1599385537:0;pip3 install pytest
: 1599385542:0;python -m pytest hello_world_test.py
: 1599385622:0;exercism submit .
: 1599385667:0;export
: 1599385677:0;export | grep EXERCISM
: 1599385681:0;export | grep exerci
: 1599385773:0;echo $EXERCISM_WORKSPACE
: 1599385829:0;ped
: 1599385830:0;pwd
: 1599385937:0;echo $EXERCISM_WORKSPACE
: 1599385938:0;ls
: 1599385944:0;clear
: 1599385993:0;ls
: 1599386013:0;cd exercism
: 1599386013:0;ls
: 1599386054:0;cd ..
: 1599386054:0;ls
: 1599386062:0;rm -R exercism
: 1599386063:0;ls
: 1599386089:0;echo $EXERCISM_WORKSPACE
: 1599386151:0;ln -s /home/chile/snap/exercism/5/exercism /home/chile/PycharmProjects/Github/MyProjects/python
: 1599386166:0;cd exercism
: 1599386176:0;cd python/hello-world
: 1599386199:0;exercism submit hello_world.py
: 1599386482:0;exercism download --exercise=two-fer --track=python
: 1599386490:0;cd ..
: 1599387237:0;clear
: 1599387371:0;exercism submit two-fer/two_fer.py
: 1599387396:0;python -m pytest two-fer/two_fer_test.py
: 1599387491:0;exercism submit two-fer/two_fer.py
: 1599388259:0;clera
: 1599388263:0;clear
: 1599443784:0;docker-compose up -d
: 1599443826:0;docker ps
: 1599443834:0;docker-compose up -d
: 1599443841:0;docker ps
: 1599443847:0;docker exec -it a2b0f45e64ea bash
: 1599443865:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599443888:0;git s
: 1599443894:0;git tree
: 1599443925:0;docker ps
: 1599443931:0;docker exec -it 767b60f7610e /bin/bash
: 1599444258:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599444407:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599444526:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599444535:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599444587:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599444592:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599445766:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599445770:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599447929:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599449635:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599449760:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599449762:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599452814:0;git stash save "testing stream flow..."
: 1599453070:0;git pull origin fix_session_with
: 1599453077:0;git s
: 1599453726:0;git a prile/.
: 1599453740:0;git cm "add 2 line debug"
: 1599453743:0;git s
: 1599453745:0;git tree
: 1599453785:0;git cob test-branch
: 1599454313:0;git s
: 1599454320:0;git a prile/.
: 1599454328:0;git cm "test git branch"
: 1599454330:0;git s
: 1599454339:0;git push origin test-branch
: 1599454360:0;git branch --help
: 1599454401:0;git co fix_session_with
: 1599454418:0;git branch -d fix_session_with
: 1599454434:0;git branch -d test-branch
: 1599454443:0;git branch -D test-branch
: 1599454456:0;git tree
: 1599454482:0;git fetch origin test-branch
: 1599454488:0;git tree
: 1599454506:0;git checkout origin test-branch
: 1599454517:0;git checkout origin/test-branch
: 1599454524:0;git tree
: 1599454555:0;git s
: 1599454561:0;git cm "add line 2"
: 1599454567:0;git s
: 1599454574:0;git a prile/.
: 1599454579:0;git cm "add line 2"
: 1599454582:0;git s
: 1599454591:0;git push origin origin/test-branch
: 1599454715:0;git s
: 1599454718:0;git tree
: 1599454765:0;git push origin test-branch
: 1599454801:0;git tree
: 1599454900:0;git reset HEAD~
: 1599454907:0;git tree
: 1599454939:0;git s
: 1599454943:0;git tree
: 1599454973:0;git cob test-branch origin/test-branch
: 1599454976:0;git tree
: 1599454987:0;git s
: 1599454998:0;git a prile/.
: 1599455020:0;git cm "add line 2 checkouted local branch"
: 1599455038:0;git push origin test-branch
: 1599456634:0;git tree
: 1599456685:0;git co fix_session_with
: 1599456702:0;git branch -D test-branch
: 1599456730:0;git push origin --delete test-branch
: 1599456785:0;git s
: 1599456798:0;git stash list
: 1599458294:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599458327:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599458348:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085203"}'
: 1599458492:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599458495:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085203"}'
: 1599458503:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085303"}'
: 1599459319:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599459829:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599459925:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599460100:0;clear
: 1599460108:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599460144:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085304"}'
: 1599461351:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599461358:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599461410:0;git s
: 1599461599:0;git a prile/.
: 1599461641:0;git cm "merge two session into one"
: 1599461676:0;git stash pop
: 1599461775:0;git s
: 1599461856:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599468922:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085305"}'
: 1599468940:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599469178:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599469187:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599469716:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599469720:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085204}'
: 1599469819:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599469829:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085205}'
: 1599469967:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599469969:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085205}'
: 1599470000:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599470006:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085206}'
: 1599470619:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085208}'
: 1599470876:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085209}'
: 1599470962:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599470964:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085209}'
: 1599470984:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599470986:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085209}'
: 1599471059:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599471065:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085210}'
: 1599471123:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599471126:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085210}'
: 1599471155:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599471222:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599471226:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085210}'
: 1599471659:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599471662:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085210}'
: 1599471776:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599471781:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599471834:0;clear
: 1599471836:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599471846:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599471981:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599472177:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599472185:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599472603:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599472616:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599472832:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599472848:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599472954:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599472957:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599473084:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599473087:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085211}'
: 1599473239:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1599473250:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085203"}'
: 1599473255:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085204"}'
: 1599473261:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085205"}'
: 1599473272:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085305"}'
: 1599473277:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598086305"}'
: 1599473376:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599473441:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931880}'
: 1599473504:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599473827:0;git s
: 1599473833:0;git a prile/.
: 1599473879:0;git cm "back session with but not support async"
: 1599475480:0;docker ps
: 1599475508:0;docker exec -it a2b0f45e64ea bash
: 1599476187:0;git s
: 1599531527:0;docker-compose up -d
: 1599531891:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599531897:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599532170:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599532172:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599532206:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599532208:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599532337:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599532340:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599532389:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599532391:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599532405:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599532412:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599532437:0;faust -A prile.workflows.profile_update.app worker -l info 
: 1599532451:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599532467:0;clear
: 1599532470:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599532981:0;pip3 install .
: 1599532992:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599533024:0;docker-compose up -d
: 1599533035:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599533143:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599533297:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599533348:0;faust -A prile.workflows.profile_update.app worker -l info
: 1599533359:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599533679:0;faust -A prile.workflows.segments_users_update.app worker
: 1599534069:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598085203}'
: 1599534096:0;faust -A prile.workflows.segments_users_update.app worker
: 1599534179:0;clear
: 1599534225:0;faust -A prile.workflows.segments_users_update.app worker
: 1599534350:0;sudo faust -A prile.workflows.segments_users_update.app worker
: 1599534358:0;faust -A prile.workflows.segments_users_update.app worker
: 1599534372:0;docker-compose up -d
: 1599534386:0;faust -A prile.workflows.segments_users_update.app worker
: 1599534406:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599534458:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085203"}'
: 1599534480:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599534486:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085203"}'
: 1599534493:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":6, "segment":"s1", "state": "in", "user":"a1", "at":"1598085204"}'
: 1599534517:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1598085203"}'
: 1599534554:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320073"}'
: 1599534604:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599534614:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":10, "segment":"s1", "state": "in", "user":"a1", "at":"1599320074"}'
: 1599534900:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599534918:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "in", "user":"a2", "at":"1599320075"}'
: 1599535029:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599535034:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "in", "user":"a2", "at":"1599320075"}'
: 1599535038:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "in", "user":"a3", "at":"1599320076"}'
: 1599535041:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "in", "user":"a4", "at":"1599320077"}'
: 1599535044:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "in", "user":"a5", "at":"1599320078"}'
: 1599535048:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "in", "user":"a6", "at":"1599320079"}'
: 1599535058:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "in", "user":"a7", "at":"1599320080"}'
: 1599535175:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s2", "state": "in", "user":"a7", "at":"1599320081"}'
: 1599535179:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s3", "state": "in", "user":"a7", "at":"1599320082"}'
: 1599535182:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s4", "state": "in", "user":"a7", "at":"1599320083"}'
: 1599535186:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s5", "state": "in", "user":"a7", "at":"1599320084"}'
: 1599535354:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a2", "at":"1599320084"}'
: 1599535361:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a3", "at":"1599320085"}'
: 1599535365:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a4", "at":"1599320086"}'
: 1599536268:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599536307:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a5", "at":"1599320087"}'
: 1599536311:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a6", "at":"1599320088"}'
: 1599536315:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a7", "at":"1599320089"}'
: 1599536341:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a8", "at":"1599320010"}'
: 1599537812:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599537823:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a8", "at":"1599320011"}'
: 1599538336:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599538361:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599538411:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599538417:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599538549:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599538553:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599539048:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599539052:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599539093:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599539095:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599539244:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931981faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":100, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'}'
: 1599539279:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599539295:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931981faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":100, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'}'
: 1599539305:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":100, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599539456:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599539466:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":100, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599539481:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599539484:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":100, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599539879:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599539882:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":100, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599540315:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599540319:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":100, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599540345:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599540385:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599540388:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599540409:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599540411:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599540440:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599540442:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599542143:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1599542223:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599542228:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1598931980}'
: 1599542260:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599542305:0;faust -A prile.workflows.conversion_broadcast.app worker -l info
: 1599542307:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":2, "anonymous_id": "a2", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c3"],"num_properties_keys":["total_value"],"num_properties_vals":[4.5],"arr_properties_keys":[""],"arr_properties_vals":[[]],"at":1599113277}'
: 1599542811:0;sudo add-apt-repository ppa:nm-l2tp/network-manager-l2tp
: 1599542843:0;sudo apt-get update
: 1599542859:0;sudo apt-get install network-manager-l2tp  network-manager-l2tp-gnome
: 1599543102:0;telnet 10.110.1.5 22
: 1599543327:0;history
: 1599543991:0;clear
: 1599543995:0;history
: 1599544011:0;telnet 10.110.1.5.22
: 1599544043:0;telnet 10.110.1.5 22
: 1599545079:0;history
: 1599545083:0;telnet 10.110.1.5 22
: 1599546181:0;ping google.com
: 1599546230:0;ping https://www.google.com/
: 1599546242:0;ping google.com
: 1599546396:0;telnet localhost
: 1599546427:0;docker-compose up -d
: 1599546444:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599546471:0;telnet localhost
: 1599546484:0;telnet  http://localhost:8500
: 1599546491:0;telnet  localhost:8500
: 1599546494:0;telnet  localhost
: 1599547430:0;git s
: 1599547441:0;git a prile/.
: 1599547463:0;git cm "session async and refactor event stream"
: 1599547471:0;git push origin fix_session_with
: 1599547483:0;clear
: 1599547492:0;git checkout matser
: 1599547499:0;git co master
: 1599547505:0;git merge fix_session_with
: 1599547514:0;git pull origin master
: 1599547522:0;git tree
: 1599547596:0;git push origin aster
: 1599547599:0;git push origin master
: 1599547609:0;git tree
: 1599547639:0;git branch
: 1599547706:0;git branch -D feat/get_profile_api
: 1599547721:0;git branch -D fix_session_with
: 1599547753:0;git branch -D change_import_file
: 1599547761:0;git branch -D agg_by_source
: 1599547769:0;git branch -D add_exceptions
: 1599547777:0;git branch -D total-user
: 1599547789:0;git branch -D user_segments_update
: 1599547799:0;git branch -D total_user_by_segment_ts
: 1599547807:0;git branch -D total-user
: 1599547818:0;git branch -D test
: 1599547826:0;git b -D switch_view_to_execute_native
: 1599547837:0;git br -D switch_view_to_execute_native
: 1599547846:0;git br -D segment_analytics_api
: 1599547850:0;git br
: 1599547861:0;git br -D MVP-177
: 1599547868:0;git br -D MVP-218
: 1599547874:0;git br -D MVP-232-233
: 1599547881:0;git br -D MVP-244
: 1599547887:0;git br -D add_tests
: 1599547900:0;git br -D refactor_request_parameter
: 1599547910:0;git br -D refactor_segment_report
: 1599547917:0;git br
: 1599547928:0;git tree
: 1599547934:0;git co develop
: 1599547940:0;git s
: 1599547942:0;git tree
: 1599547981:0;git merge master
: 1599547984:0;git tree
: 1599547996:0;clear
: 1599548136:0;git cob test-async-await
: 1599553542:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599557020:0;ls
: 1599557021:0;clear
: 1599557023:0;ls
: 1599557051:0;clear
: 1599557702:0;pwd
: 1599557703:0;clear
: 1599557709:0;cd
: 1599557714:0;pwd
: 1599557716:0;cd PycharmProjects
: 1599557721:0;cd Github/PrimeData/event-processing
: 1599557731:0;clear
: 1599561900:0;curl https://coronavirus-tracker-api.herokuapp.com/v2/locations | json_pp
: 1599562531:0;git clone git@github.com:ExpDev07/coronavirus-tracker-api.git
: 1599563785:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599565312:0;pip3 install -r requirements.txt
: 1599565546:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599614008:0;docker-compose up -d
: 1599614016:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599614036:0;docker-compose up -d
: 1599614048:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599614483:0;git s
: 1599614572:0;git a prile/.
: 1599614611:0;git cm "convert api func to aync"
: 1599614710:0;git co master
: 1599614715:0;git merge test-async-await
: 1599614720:0;git pull master
: 1599614731:0;git pull origin master
: 1599614739:0;git push origin master
: 1599617440:0;git cob abc-interface
: 1599619576:0;git s
: 1599619609:0;git stash save "use abc module for interface"
: 1599642142:0;ipconfig
: 1599642146:0;ifconfig
: 1599703836:0;docker-compose up -d
: 1599703848:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599704998:0;docker ps
: 1599705004:0;docker exec -it 767b60f7610e /bin/bash
: 1599705983:0;ifconfig
: 1599709533:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599718126:0;ifconfig
: 1599720258:0;pip3 install -r requirements.txt
: 1599720290:0;pip3 install .
: 1599720307:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599720428:0;pip3 install -r requirements.txt
: 1599720438:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599720492:0;pip3 install .
: 1599720500:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599725072:0;pip3 install -r requirements.txt
: 1599725243:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599727444:0;pip3 install pandas 
: 1599749688:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599749695:0;docker exec -it 767b60f7610e /bin/bash
: 1599749703:0;docker-compose up -d
: 1599749708:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599749740:0;docker-compose up -d
: 1599749748:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599791277:0;docker-compose up -d
: 1599791282:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599795480:0;ifconfgi
: 1599795482:0;ifconfig
: 1599796783:0;docker ps
: 1599796800:0;docker exec -it 767b60f7610e /bin/bash
: 1599797855:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599801381:0;pip3 install humps
: 1599801791:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599811155:0;git s
: 1599811167:0;git a .
: 1599811214:0;git cm "customer api: itergrate with fronted"
: 1599812861:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1599815702:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599815716:0;docker-compose up -d
: 1599815722:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1599816038:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":20, "segment":"s1", "state": "out", "user":"a8", "at":"1599320011"}'
: 1599816057:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a1", "at":"1599320010"}'
: 1599816123:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a2", "at":"1599320011"}'
: 1599816127:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a3", "at":"1599320012"}'
: 1599816133:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a4", "at":"1599320013"}'
: 1599816137:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a5", "at":"1599320014"}'
: 1599816198:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "out", "user":"a1", "at":"1599320015"}'
: 1599816201:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s3", "state": "out", "user":"a1", "at":"1599320016"}'
: 1599816205:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s4", "state": "out", "user":"a1", "at":"1599320017"}'
: 1599816208:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s5", "state": "out", "user":"a1", "at":"1599320018"}'
: 1599817784:0;git s
: 1599817823:0;git cm "segment report api, itergrate with frontend"
: 1599817826:0;git a .
: 1599817828:0;git cm "segment report api, itergrate with frontend"
: 1599817903:0;git branch -m itegate_with_front_end
: 1599817913:0;git push origin itegate_with_front_end
: 1599817924:0;git stash list
: 1599820359:0;timedatectl | grep  \BCTime zone \BD
: 1599820370:0;cat /etc/timezone
: 1599820585:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599874520:0;sudo add-apt-repository ppa:gnome3-team/gnome3
: 1599874764:0;logout
: 1599874768:0;clear
: 1599875139:0;docker-compose up -d
: 1599876671:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599878813:0;docker ps
: 1599878821:0;docker exec -it 767b60f7610e /bin/bash
: 1599881711:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599887496:0;pip3 install -r requirements.txt
: 1599887512:0;pip3 install .
: 1599887527:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599900141:0;docker-compose up -d
: 1599900146:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599900172:0;docker-compose up -d
: 1599900177:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599906669:0;git s
: 1599906672:0;git a .
: 1599906711:0;git cm "added tranformation layer and done profile api"
: 1599910219:0;docker ps
: 1599910227:0;docker exec -it 767b60f7610e /bin/bash
: 1599964938:0;docker-compose up -d
: 1599964973:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599965259:0;docker ps
: 1599965265:0;docker exec -it 767b60f7610e /bin/bash
: 1599966642:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599986135:0;docker-compose up -d
: 1599986140:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1599986163:0;docker ps
: 1599986170:0;docker exec -it 767b60f7610e /bin/bash
: 1599988555:0;git s
: 1599988560:0;git  a .
: 1599988600:0;git cm "done all api for customer"
: 1600047438:0;docker ps
: 1600047451:0;docker-compose up -d
: 1600047460:0;docker ps
: 1600047520:0;docker exec -it 767b60f7610e /bin/bash
: 1600048146:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600049217:0;docker-compose up -d
: 1600049224:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600049242:0;docker ps
: 1600049251:0;docker exec -it 767b60f7610e /bin/bash
: 1600050006:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600050016:0;ifconfig
: 1600050913:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600052189:0;clear
: 1600057246:0;telnet 10.110.1.5 22
: 1600057263:0;ifconfig
: 1600057371:0;telnet 10.110.1.4 22
: 1600057501:0;openvpn
: 1600057527:0;ls
: 1600057532:0;cd Documents/
: 1600057532:0;ls
: 1600057535:0;cd pem
: 1600057536:0;ls
: 1600057552:0;openvpn --config chile-118.68.168.185.ovpn
: 1600057565:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600058216:0;git stash save "segment analytics fixing..."
: 1600058229:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600063797:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600064195:0;git s
: 1600064197:0;git a .
: 1600064259:0;git cm "add get all activity not filter by event name and add count total row for get sample profile"
: 1600064270:0;git push origin itegate_with_front_end
: 1600064280:0;git stash list
: 1600064320:0;git stash pop 
: 1600064879:0;git s
: 1600069090:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600072269:0;git s
: 1600072307:0;git cm "expose api for metrics segment"
: 1600073751:0;ifconfig
: 1600074336:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600083321:0;git a .
: 1600083343:0;git cm "release api get profiles by segment id"
: 1600083355:0;git push origin itegate_with_front_end
: 1600134959:0;ifconfig
: 1600135043:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600135054:0;docker-compose up -d
: 1600135062:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600135079:0;docker-compose up -d
: 1600135234:0;docker ps
: 1600135240:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600135255:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600135259:0;clear
: 1600135261:0;docker ps
: 1600135280:0;docker-compose up -d
: 1600135871:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600135930:0;git pull
: 1600135941:0;git pull origin itegate_with_front_end
: 1600135947:0;[200~uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600135951:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888\

: 1600135972:0;ls
: 1600135974:0;pwd
: 1600135985:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600135996:0;[200~uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600136004:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888\

: 1600136010:0;sudo uvicorn main:app --reload --host 0.0.0.0 --port 8888\

: 1600136025:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600136106:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600136223:0;docker ps
: 1600136281:0;docker exec -it 767b60f7610e /bin/bash
: 1600137856:0;git pull origin itegate_with_front_end
: 1600137885:0;git s
: 1600137888:0;git a .
: 1600137900:0;git cm "fix location_country key"
: 1600137908:0;git push origin itegate_with_front_end
: 1600137911:0;git pull
: 1600137924:0;git pull origin itegate_with_front_end
: 1600143529:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600143636:0;git s
: 1600143639:0;git a .
: 1600143660:0;git cm "get total user time series - first"
: 1600143671:0;git pull origin itegate_with_front_end
: 1600143687:0;git push origin itegate_with_front_end
: 1600143692:0;git pull origin itegate_with_front_end
: 1600152439:0;git a
: 1600152441:0;git s
: 1600152443:0;git a .
: 1600152473:0;git cm "add histogram schema json"
: 1600152479:0;git push origin itegate_with_front_end
: 1600152484:0;git pull
: 1600152494:0;git push origin itegate_with_front_end
: 1600152514:0;git pull origin itegate_with_front_end
: 1600153204:0;git commit -am "edit schema json histogram"
: 1600153208:0;git push origin itegate_with_front_end
: 1600153214:0;git pull origin itegate_with_front_end
: 1600157363:0;git checkout master
: 1600157378:0;git s
: 1600157387:0;git a .
: 1600157454:0;git cm "rename page_size to perPage to sync with bro Truong"
: 1600157459:0;git s
: 1600157462:0;git checkout master
: 1600157470:0;git pull origin master
: 1600157859:0;git tree
: 1600157890:0;git merge itegate_with_front_end
: 1600157938:0;git checkout itegate_with_front_end
: 1600158222:0;git tree
: 1600158796:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600164458:0;git s
: 1600164460:0;git a .
: 1600164474:0;git cm "get histogram data by metric name"
: 1600164479:0;git push origin itegate_with_front_end
: 1600164487:0;git pull origin itegate_with_front_end
: 1600165710:0;git cm "get histogram data by metric na
: 1600165711:0;clear
: 1600165712:0;git s
: 1600165714:0;git a 
: 1600165742:0;git cm "add value: float, api get histogram data"
: 1600165748:0;git push origin itegate_with_front_end
: 1600165766:0;git a .
: 1600165768:0;git cm "add value: float, api get histogram data"
: 1600165770:0;git push origin itegate_with_front_end
: 1600165777:0;git pull origin itegate_with_front_end
: 1600166597:0;git s
: 1600166612:0;git a .
: 1600166628:0;git cm "rename page size to per_page"
: 1600166631:0;git push origin itegate_with_front_end
: 1600166644:0;git pull origin itegate_with_front_end
: 1600167257:0;sudo openvpn --config /Docchile-118.68.168.185.ovpn
: 1600167265:0;cd /home
: 1600167266:0;ls
: 1600167268:0;cd chile
: 1600167269:0;ls
: 1600167274:0;cd Documents
: 1600167275:0;ls
: 1600167277:0;cd p
: 1600167280:0;cd pem
: 1600167283:0;sudo openvpn --config /Docchile-118.68.168.185.ovpn
: 1600167297:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600169271:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600169339:0;cd /home/chile/Documents/pem
: 1600169340:0;ls
: 1600169343:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600217736:0;git s
: 1600217746:0;git status
: 1600217809:0;docker-compose
: 1600217813:0;docker-compose up -d
: 1600217823:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600218991:0;docker ps
: 1600218998:0;docker exec -it 767b60f7610e /bin/bash
: 1600219330:0;cd /home/chile/Documents/pem
: 1600219333:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600220753:0;ifconfig
: 1600220783:0;git pull origin itegate_with_front_end
: 1600220795:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600221079:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600221230:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600227071:0;curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl\

: 1600227095:0;chmod +x ./kubectl
: 1600227102:0;sudo mv ./kubectl /usr/local/bin/kubectl
: 1600227124:0;[200~kubectl version~
: 1600227126:0;kubectl version
: 1600227337:0;cd
: 1600227341:0;ls
: 1600227361:0;which kubeclt
: 1600227369:0;kubeclt
: 1600227378:0;kubectl 
: 1600227382:0;which kubectl 
: 1600227411:0;nano ~/.kubectl/config
: 1600227461:0;mkdir ~/.kubectl
: 1600227468:0;ls -la
: 1600227477:0;cd .kubectl
: 1600227572:0;mkdir config
: 1600227573:0;ls
: 1600227575:0;cd config
: 1600227682:0;pwd
: 1600227692:0;cp config-primedata /home/chile/.kubectl/config
: 1600227695:0;ls
: 1600227705:0;clear
: 1600227759:0;kubectl port-forward svc/consul-ui 8500:80
: 1600227777:0;docker ps
: 1600227875:0;cd /etc
: 1600227875:0;ls
: 1600227880:0;nano hosts
: 1600227906:0;sudo nano hosts
: 1600228850:0;git s
: 1600228921:0;git a .
: 1600228940:0;git cm "
: 1600228980:0;git cm "preparing code get total user by segment ts and comment ip clickhouse in file test"
: 1600228992:0;git checkout master
: 1600228997:0;git merge itegate_with_front_end
: 1600229002:0;git push origin master
: 1600229569:0;vi hosts
: 1600229594:0;kubectl get po
: 1600229635:0;kubectl config get-context
: 1600229636:0;kubectl config get-contexts
: 1600229656:0;cat ~/.kube/config
: 1600229683:0;cp ~/.kubectl/config/config-primedata ~/.kube/config
: 1600229688:0;mkdir ~/.kube
: 1600229694:0;cp ~/.kubectl/config/config-primedata ~/.kube/config
: 1600229700:0;kubectl config get-contexts
: 1600229704:0;kubectl get po 
: 1600229738:0;kubectl get po | grep event-processing
: 1600229820:0;kubectl logs -f event-processing-dcbcc8dcc-px89m
: 1600229840:0;clear
: 1600229844:0;kubectl get po | grep event-processing
: 1600229875:0;kubectl get svc
: 1600229882:0;clear
: 1600229884:0;kubectl get po | grep event-processing
: 1600229889:0;kubectl logs -f event-processing-dcbcc8dcc-px89m
: 1600229909:0;kubectl port-forward svc/consul-ui 8500:80
: 1600229921:0;kubectl port-forward svc/consul-ui 8501:80
: 1600230069:0;kubectl get po | grep event-processing
: 1600230105:0;clear
: 1600230245:0;git checkout master
: 1600230247:0;git s
: 1600230251:0;git push origin master
: 1600230270:0;git tree
: 1600230278:0;git pull origin master
: 1600230315:0;git s
: 1600230333:0;git cm "update master\
"
: 1600230337:0;git push origin master
: 1600230436:0;history
: 1600230495:0;clear
: 1600230739:0;history
: 1600230753:0;kubectl get po | grep event-processing
: 1600230790:0;kubectl logs -f event-processing-54d4f78b69-87dqt 
: 1600230859:0;git tree
: 1600230881:0;git checkout itegate_with_front_end
: 1600230891:0;git merge master
: 1600230896:0;git s
: 1600230900:0;git tree
: 1600230973:0;kubectl port-forward svc/consul-ui 8501:80
: 1600231036:0;kubectl get po | grep event-processing
: 1600231042:0;kubectl delete po v
: 1600231049:0;kubectl delete po event-processing-54d4f78b69-87dqt
: 1600231121:0;kubectl get po 
: 1600231124:0;(.prile) (base)  chile@Lati-7480 \B0 ~/PycharmProjects/Github/PrimeData/event-processing \B0 \83\80 itegate_with_front_end \B0 
: 1600231130:0;kubectl get po | grep event
: 1600231151:0;kubectl edit deployment event-processing
: 1600231283:0;kubectl get po | grep event
: 1600231296:0;kubectl logs -f event-processing-54d4f78b69-87dqt
: 1600231316:0;kubectl get po | grep event
: 1600231335:0;kubectl logs -f event-processing-54d4f78b69-nlpd8
: 1600231429:0;kubectl get svc
: 1600231434:0;kubectl get svc | grep event
: 1600231466:0;kubectl port-forward svc/event-processing 8889:8888
: 1600231523:0;clear
: 1600231531:0;pip3 install -r requirements.txt
: 1600231619:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600237748:0;git s
: 1600239097:0;git a .
: 1600239146:0;git cm "remove datetime range and add  metric agg in hist data"
: 1600239150:0;git push origin master
: 1600239199:0;git checkout develop
: 1600239207:0;git merge master
: 1600239215:0;git tree
: 1600239226:0;git merge itegate_with_front_end
: 1600239230:0;git tree
: 1600239238:0;git push origin develop
: 1600239374:0;git tree
: 1600251042:0;docker ps -a 
: 1600251046:0;docker ps 
: 1600251057:0;docker exec -it insert into segment_users values
: 1600251110:0;(1, 's600', ['a1', 'a2','a3','a4'], '2020-09-16 03:03:03');clear
: 1600251127:0;docker exec -it 767b60f7610e /bin/bash
: 1600253173:0;cat /etc/timezone
: 1600253176:0;date
: 1600308666:0;cd /home/chile/Documents/pem
: 1600308671:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600308690:0;docker-compose up -d
: 1600308908:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600310784:0;git s
: 1600310787:0;git a .
: 1600310813:0;git cm "total user ts api base"
: 1600310817:0;git push origin  develop
: 1600333536:0;git s
: 1600333538:0;git a .
: 1600333547:0;git cm "data source api"
: 1600333553:0;git push origin develop
: 1600350279:0;docker-compose up -d
: 1600350316:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600350382:0;fit s
: 1600350383:0;git s
: 1600350387:0;git a .
: 1600350417:0;git cm "get total user by data source use sql not use pandas"
: 1600350423:0;git push origin develop
: 1600350914:0;git s
: 1600354039:0;cd /home/chile/Documents/pem
: 1600354043:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600354257:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1600355071:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600391644:0;docker-compose up -d
: 1600391651:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600393583:0;cd /home/chile/Documents/pem
: 1600393587:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600393637:0;git s
: 1600393668:0;git cm "trying inject dependency in init"
: 1600393674:0;git push origin develop
: 1600393687:0;docker-compose up -d
: 1600393694:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600406394:0;git s
: 1600406423:0;git cm "get total user time series api done"
: 1600406428:0;git push origin develop
: 1600406439:0;git a .
: 1600406441:0;git cm "get total user time series api done"
: 1600406444:0;git push origin develop
: 1600407714:0;git s
: 1600412790:0;git a .
: 1600412801:0;git cm "fix data source total user"
: 1600412805:0;git push origin develop
: 1600416144:0;git s
: 1600416165:0;git stash save "refactor datasource"
: 1600416206:0;git cb transformation_is_service_layer
: 1600416220:0;git checkout -b transformation_is_service_layer
: 1600416228:0;git stash pop
: 1600416245:0;git s
: 1600416252:0;git checkout develop
: 1600416280:0;git stash list
: 1600416290:0;git checkout transformation_is_service_layer
: 1600416294:0;git s
: 1600417504:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600419495:0;git s
: 1600419497:0;git a .
: 1600419524:0;git cm "data source refactor, not use service"
: 1600428279:0;git s
: 1600428282:0;git a .
: 1600429176:0;git cm "refactor segment report"
: 1600429204:0;git push origin transformation_is_service_layer
: 1600479876:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600652832:0;git s
: 1600652833:0;git tree
: 1600652861:0;docker-compose up -d
: 1600652873:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600653003:0;cd /home/chile/Documents/pem
: 1600653005:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600653010:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600653059:0;docker-compose up -d
: 1600653080:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600653207:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600653229:0;git s
: 1600653254:0;git cm "wrapper dict to entity, report api"
: 1600653259:0;git a .
: 1600653260:0;git cm "wrapper dict to entity, report api"
: 1600653265:0;git push origin transformation_is_service_layer
: 1600653311:0;git checkout develop
: 1600653316:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600653477:0;docker-compose up -d
: 1600653537:0;cd /home/chile/Documents/pem
: 1600653541:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600653554:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600653622:0;git checkout transformation_is_service_layer
: 1600655151:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600655536:0;git s
: 1600655572:0;docker ps 
: 1600655578:0;docker exec -it 767b60f7610e /bin/bash
: 1600656510:0;git s
: 1600656525:0;git a .
: 1600656531:0;git cm "format sql code"
: 1600656537:0;git push origin transformation_is_service_layer
: 1600659820:0;git checkout develop
: 1600659826:0;git merge transformation_is_service_layer
: 1600660033:0;git checkout master
: 1600660099:0;git pull origin master
: 1600660106:0;git merge develop
: 1600660109:0;git tree
: 1600660247:0;git checkout develop
: 1600660350:0;git a .
: 1600660382:0;git cm "rename field name of DSTotalUser"
: 1600660388:0;git s
: 1600660442:0;git status
: 1600661320:0;git tree
: 1600661335:0;git s
: 1600661340:0;git a .
: 1600661363:0;git cm "format sql code data source"
: 1600661371:0;git push origin develop
: 1600661378:0;git tree
: 1600662216:0;git s
: 1600662783:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600662788:0;git s
: 1600662808:0;git add .
: 1600662828:0;git cm "remove garbage and format files"
: 1600662831:0;git push origin develop
: 1600662841:0;git tree
: 1600665961:0;git s
: 1600665964:0;git a .
: 1600665980:0;git cm "user profile: move sql code to a file"
: 1600665986:0;git push origin develop
: 1600670979:0;docker-compose up -d
: 1600670992:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600671662:0;cd /home/chile/Documents/pem
: 1600671678:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600672631:0;docker ps
: 1600672645:0;docker exec -it 767b60f7610e /bin/bash
: 1600680519:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600682566:0;git s
: 1600682568:0;git a .
: 1600682619:0;git cm "use field common for sql"
: 1600682628:0;git push origin develop
: 1600738490:0;git s
: 1600738525:0;git a .
: 1600738531:0;git cm "rename variable"
: 1600738570:0;docker-compose up -d
: 1600738592:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600738611:0;cd /home/chile/Documents/pem
: 1600738625:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600738631:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600740504:0;git s
: 1600740583:0;git cm "replace Pagination entity to page, per page"
: 1600740586:0;git s
: 1600740589:0;git a 
: 1600740594:0;git cm "replace Pagination entity to page, per page"
: 1600740596:0;git s
: 1600740606:0;git a .
: 1600740609:0;git s
: 1600740614:0;git cm "replace Pagination entity to page, per page"
: 1600740619:0;git push origin develop
: 1600743727:0;git s
: 1600743729:0;git cm 
: 1600743732:0;git a .
: 1600743838:0;git cm "use property key constant for global variables"
: 1600743849:0;git push origin develop
: 1600746090:0;git s
: 1600746092:0;git a .
: 1600746101:0;git cm "rename router to V1"
: 1600747085:0;git a .
: 1600747180:0;git cm "refactor total_metric_value func use sum map lambda"
: 1600747324:0;git push origin develop
: 1600747332:0;git tree
: 1600749633:0;git s
: 1600749660:0;git cm "add extract emails func to support multi email after"
: 1600749675:0;git s
: 1600750722:0;git a .
: 1600750751:0;git cm "split data transform to 2 file"
: 1600750756:0;git push origin develop
: 1600760191:0;pip3 install -r requirements.txt
: 1600760199:0;pip3 install .
: 1600760217:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600761930:0;git s
: 1600761933:0;git a .
: 1600761969:0;git cm "clickhouse drive update 0.1.5 supported get nested array"
: 1600761975:0;git push origin develop
: 1600762022:0;git checkout master
: 1600762024:0;git merge develop
: 1600762082:0;git tree
: 1600762096:0;git push origin master
: 1600762106:0;git tree
: 1600762871:0;pip3 install clickhouse-driver
: 1600763142:0;clear
: 1600763145:0;docker ps
: 1600763152:0;docker exec -it 767b60f7610e /bin/bash
: 1600765291:0;git s
: 1600765293:0;git a .
: 1600765314:0;git cm "fixed missing dot"
: 1600765920:0;git tree
: 1600765927:0;git checkout develop
: 1600765932:0;git merge master
: 1600765948:0;git tree
: 1600766596:0;docker ps
: 1600766610:0;docker exec -it 767b60f7610e /bin/bash
: 1600825590:0;docker-compose up -d
: 1600825610:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600825639:0;cd /home/chile/Documents/pem
: 1600825644:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600826558:0;docker ps
: 1600826574:0;docker exec -it 767b60f7610e /bin/bash
: 1600848924:0;git s
: 1600848927:0;git a .
: 1600848951:0;git cm "fixing time zone utc -> local "
: 1600848956:0;git push origin develop
: 1600854438:0;git s
: 1600854440:0;git a .
: 1600854463:0;git cm "alias name for start end time range request"
: 1600854468:0;git push origin develop
: 1600855480:0;git a .
: 1600855512:0;git cm "add request time range sent to server to response"
: 1600860955:0;git a .
: 1600860964:0;git tree
: 1600860995:0;git cm "fixing time series range utc and local"
: 1600860998:0;git push origin develop
: 1600912699:0;docker compose up -d
: 1600912902:0;docker-compose up -d
: 1600912915:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1600913156:0;cd /home/chile/Documents/pem
: 1600913158:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600914750:0;git s
: 1600914753:0;git a .
: 1600914775:0;git cm "split two 2 sql query"
: 1600914780:0;git push origin develop
: 1600917085:0;docker-compose up -d
: 1600917335:0;faust -A prile.workflows.segments_users_update.app worker -l info
: 1600917409:0;git s
: 1600917442:0;git cm "refine segments users update stream"
: 1600917445:0;git s
: 1600917451:0;git a .
: 1600917453:0;git cm "refine segments users update stream"
: 1600917454:0;git s
: 1600927827:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600927940:0;docker ps
: 1600927972:0;docker --help | grep network
: 1600927976:0;docker --help
: 1600928006:0;docker restart --help
: 1600928021:0;docker ps
: 1600928056:0;docker stop $(docker ps -aq)
: 1600928068:0;docker ps
: 1600928076:0;docker-compose up -d
: 1600928196:0;docker ps
: 1600928230:0;clear
: 1600928233:0;docker ps
: 1600928242:0;docker-compose up -d
: 1600928247:0;docker ps
: 1600928290:0;docker exec -it efa7b517aa29 /bin/bash
: 1600928472:0;clear
: 1600928483:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600928947:0;docker ps
: 1600928954:0;docker exec -it 767b60f7610e /bin/bash
: 1600929166:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a1", "event_name": "View Product", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency","campaign_name"],"str_properties_vals":["VND","c1"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600928968}'
: 1600929234:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : [1], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600929279:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600929283:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : [1], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600929447:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600929570:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : [1], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600929576:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600929762:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":"25", "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : [1], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600930008:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600930084:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":"25", "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : [1], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600930481:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600930484:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":"25", "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : [1], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600930602:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600930605:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":"25", "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : [1], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600931000:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a1", "identity_keys":["user_id"], "identity_vals" : ["1"], "str_properties_keys":["gender"],"str_properties_vals":["male"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":[],"arr_properties_vals":[],"at":1600928968}'
: 1600931213:0;clear
: 1600931330:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a1", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","chile@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":["first_activity"],"num_properties_vals":[1600931072],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931072}'
: 1600933283:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a1", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","chilevan74@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":["first_activity"],"num_properties_vals":[1600931072],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931072}'
: 1600933612:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600933618:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a1", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","chilevan74@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":["first_activity"],"num_properties_vals":[1600931072],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931072}'
: 1600933676:0;git s
: 1600933677:0;git a .
: 1600933733:0;git cm "user profile entity change => edited profile update stream"
: 1600933738:0;git push origin develop
: 1600934013:0;clear
: 1600937437:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1600938139:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a1", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931080}'
: 1600938325:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a2", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931080}'
: 1600938432:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a2", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","test@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931080}'
: 1600939041:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a2", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":[],"str_properties_vals":[],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931083}'
: 1600939054:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600939066:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a2", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":[],"str_properties_vals":[],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931085}'
: 1600939123:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1600939130:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a2", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":[],"str_properties_vals":[],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931085}'
: 1600939164:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a2", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[3],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931086}'
: 1600939458:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a2", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1600939656:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1600939673:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a3", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1600939712:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a3", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","test@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931090}'
: 1600939718:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a3", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1600939979:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1600939988:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a4", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","test@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931090}'
: 1600940011:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1600940112:0;select * from user_profile_final_v where tenant_id = 25 and anonymous_id = 'a3';faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1600940116:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1600940145:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1600940151:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1600941037:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931091}'
: 1600943099:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931092}'
: 1600943268:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600942370}'
: 1600943330:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a5", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","test@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931090}'
: 1600943441:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a5", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600943433}'
: 1600943514:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a5", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600943430}'
: 1600943665:0;git s
: 1600943667:0;git a .
: 1600943680:0;git tree
: 1600943711:0;git cm "user profile entity change => edited conversion brocadcast and tested"
: 1600944406:0;git a .
: 1600944451:0;git cm "alternative properties string to const"
: 1600945461:0;git s
: 1600945468:0;git a .
: 1600945489:0;git cm "alternative properties string to const in profile update processer"
: 1600945756:0;pip3 install -r requirements.txt
: 1600945927:0;pip3 install currencyconverter
: 1600946314:0;git s
: 1600946337:0;git a .
: 1600946347:0;git cm "added concyrency enum"
: 1600946352:0;git push origin develop
: 1600959315:0;git clone git@github.com:minotaurebh/Stream_Twitter.git
: 1600998041:0;docker-compose up -d
: 1600998232:0;cd /home/chile/Documents/pem
: 1600998235:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1600998345:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1600998704:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1600998743:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a5", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600943435}'
: 1600998849:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1600998858:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a5", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600943435}'
: 1601003629:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601005807:0;git s
: 1601005970:0;git a prile/common/enums.py prile/common/property_key_consts.py prile/eventify/repository/segment_reports.py prile/eventify/transformation/segment_reports.py prile/workflows/conversion_broadcast/agents.py
: 1601005971:0;git s
: 1601006008:0;git a prile/http/routers/segment_report.py
: 1601006009:0;git s
: 1601006068:0;git cm "added conversion properties const and mapping with metric names\
"
: 1601006070:0;git s
: 1601006073:0;git a .
: 1601006120:0;git cm "fix NaN value return from DB, use OrDefault"
: 1601006122:0;git s
: 1601006128:0;git push origin develop
: 1601006212:0;git tree
: 1601006979:0;docker ps
: 1601006985:0;docker exec -it 767b60f7610e /bin/bash
: 1601007942:0;git s
: 1601007967:0;git cm "update event and event total user by source ts schema sql"
: 1601007974:0;git a .
: 1601007975:0;git cm "update event and event total user by source ts schema sql"
: 1601007979:0;git push origin master
: 1601008512:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":25, "anonymous_id": "a4", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","test@gmail.com"], "str_properties_keys":["gender","location_city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931090}'
: 1601008529:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[4],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600931087}'
: 1601008927:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":25, "anonymous_id": "a4", "event_name": "Buy IPHONE", "identity_keys":["user_id"], "identity_vals" : ["levanchi"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1600942372}'
: 1601009304:0;git s
: 1601009322:0;git a .
: 1601009336:0;git cm "rename revenue properties key"
: 1601009341:0;git push origin develop
: 1601009472:0;git co master
: 1601009475:0;git merge develop
: 1601009478:0;git tree
: 1601009493:0;git push origin master
: 1601009501:0;git tree
: 1601090394:0;docker-compose up -d
: 1601106146:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601106169:0;cd /home/chile/Documents/pem
: 1601106175:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601171590:0;docker-compose up -d
: 1601174687:0;cd /home/chile/Documents/pem
: 1601174691:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601174907:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601257224:0;sudo apt install flameshot
: 1601257903:0;flameshot
: 1601258091:0;git s
: 1601258113:0;git a .
: 1601258209:0;git cm "added session id key"
: 1601258218:0;git push origin master
: 1601258226:0;git tree
: 1601258237:0;git checkout develop
: 1601258245:0;git merge master
: 1601258252:0;git tree
: 1601258261:0;git push origin develop
: 1601258269:0;git tree
: 1601258297:0;docker-compose up -d
: 1601258307:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601258708:0;cd /home/chile/Documents/pem
: 1601258710:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601261338:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601261535:0;git add .
: 1601261566:0;git cm "alternative user profile entity"
: 1601277388:0;git a .
: 1601277418:0;git cm "refactor entity class"
: 1601277421:0;git push origin develop
: 1601281619:0;pip install requests
: 1601283885:0;git s
: 1601283961:0;git cm "added Currency convertor class"
: 1601284400:0;git s
: 1601284404:0;git a .
: 1601284407:0;git cm "added Currency convertor class"
: 1601284410:0;git s
: 1601292236:0;git cm "edited sql when source became to channels array"
: 1601292239:0;git s
: 1601292244:0;git a .
: 1601292244:0;git s
: 1601292251:0;git cm "edited sql when source became to channels array"
: 1601292262:0;git push origin develop
: 1601343314:0;cd /home/chile/Documents/pem
: 1601343317:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601343329:0;docker-compose up -d
: 1601343347:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601343361:0;docker-compose up -d
: 1601343367:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601343823:0;git clone [200~git@github.com:ClickHouse/clickhouse-presentations.git~
: 1601343835:0;git clone git@github.com:ClickHouse/clickhouse-presentations.git
: 1601343935:0;git s
: 1601343940:0;git tree
: 1601344426:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1601344466:0;docker ps
: 1601344500:0;docker exec -it efa7b517aa29 /bin/bash
: 1601344797:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id", "email"], "identity_vals" : ["user_1","chilevan74@gmail.com"], "str_properties_keys":["gender","city"],"str_properties_vals":["male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","google"]],"at":1601344766}'
: 1601345115:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["user_1","chile74@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["google","mailchim"]],"at":1601345105}'
: 1601345336:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a2", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["user_2","user2@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Female","Ha Noi"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","google"]],"at":1601345306}'
: 1601345401:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6068
: 1601345534:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1601345507"}'
: 1601345635:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a2", "at":"1601345585"}'
: 1601349210:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s2", "state": "in", "user":"a1", "at":"1601349196"}'
: 1601349680:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1601349703:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1601349714:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601349660}'
: 1601349792:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1601349798:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[5000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601349660}'
: 1601351749:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone 7", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[12000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601351692}'
: 1601352192:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "Buy Xiaomi 7", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[3000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601352169}'
: 1601353448:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a3", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["user_3","user3@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Female","Ha Noi"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","google"]],"at":1601337600}'
: 1601353530:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "Buy Xiaomi 7", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601353477}'
: 1601353571:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601353477}'
: 1601354964:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a2", "event_name": "Buy Xiaomi 7", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[10],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601354923}'
: 1601355339:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601354925}'
: 1601355370:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1601355386:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":["user_id"], "identity_vals" : ["doi_ko"], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[1],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["val1","val2"]],"at":1601354926}'
: 1601355640:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone 11", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601354930}'
: 1601355736:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1601355740:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1601355756:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone 11", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601354935}'
: 1601355974:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1601355984:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone 11", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601354935}'
: 1601356068:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1601356075:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone 11", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601354935}'
: 1601356148:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1601356151:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone 11", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601354935}'
: 1601356410:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Iphone 11", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601354940}'
: 1601356542:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a3", "at":"1601356531"}'
: 1601356631:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["USD"],"num_properties_keys":["total_value"],"num_properties_vals":[2],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601356615}'
: 1601356711:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601356620}'
: 1601356830:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "out", "user":"a3", "at":"1601356535"}'
: 1601364297:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601364818:0;faust -A prile.workflows.eventify-events.app send "eventify_event_topic"  '{"tenant_id":1,"event_id": "event1", "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601356620}'
: 1601364834:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"tenant_id":1,"event_id": "event1", "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601356620}'
: 1601364847:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601364862:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"tenant_id":1,"event_id": "event1", "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601356620}'
: 1601365012:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601365018:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"tenant_id":1,"event_id": "event1", "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601356620}'
: 1601365415:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601365545:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"tenant_id":1,"event_id": "event1", "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601356620}'
: 1601365658:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601365662:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"tenant_id":1,"event_id": "event1", "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601356620}'
: 1601366119:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"tenant_id":1,"event_id": "event1", "anonymous_id": "a1", "event_name": "Buy Xiaomi 12", "identity_keys":["user_id","email"], "identity_vals" : ["user-chi","user1@gmail.com"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601366065}'
: 1601366492:0;git s
: 1601366496:0;git a .
: 1601366546:0;git cm "testing and fixed small bugs in streaming, add eventify event process workflow"
: 1601366548:0;git s
: 1601366551:0;git push origin develop
: 1601370632:0;git s
: 1601371820:0;git a .
: 1601371887:0;git cm "current have a little data, will return all properties"
: 1601371889:0;git s
: 1601373080:0;git stash save "trying return properties key, val"
: 1601373708:0;git s
: 1601373710:0;git a .
: 1601373732:0;git cm "back to not return all properties"
: 1601373797:0;git tree
: 1601376753:0;git s
: 1601376960:0;git push origin develop
: 1601430360:0;docker-compose up -d
: 1601430488:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601430516:0;cd /home/chile/Documents/pem
: 1601430519:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601516677:0;git s
: 1601516693:0;git a .
: 1601516695:0;git cm 
: 1601516815:0;git cm "change event id to id field"
: 1601516823:0;git push origin develop
: 1601516954:0;cd /home/chile/Documents/pem
: 1601516956:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601517350:0;docker-compose up -d
: 1601517359:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601527662:0;git a .
: 1601527689:0;git cm "expose user proifle metric api"
: 1601527693:0;git push origin develop
: 1601532533:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601532606:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1601532721:0;pip3 install -r requirements.txt
: 1601532725:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1601532824:0;telnet 10.110.1.5:19092
: 1601532834:0;telnet 10.110.1.5
: 1601532853:0;telnet 10.110.1.4
: 1601532865:0;telnet 10.110.1.5
: 1601532994:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1601534402:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601535981:0;git s
: 1601535983:0;git a .
: 1601536005:0;git cm "rename metric have histogram enum"
: 1601536009:0;git push origin develop
: 1601536120:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601538191:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601538588:0;telnet 10.110.1.5 19092
: 1601538920:0;clear
: 1601539175:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601540247:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"
: 1601540250:0;'{"id": "id-xxx", "tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 12", "identity_keys":["user_id","email"], "identity_vals" : ["user-chi","user1@gmail.com"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601540035}'
: 1601540273:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic "'{"id": "id-xxx", "tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 12", "identity_keys":["user_id","email"], "identity_vals" : ["user-chi","user1@gmail.com"], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2"]],"at":1601540035}'
: 1601540332:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601540415:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"id": "event-xxx","tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601540035}'
: 1601540465:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id": "event-xxx","tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601540035}'
: 1601540618:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601540626:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id": "event-xxx","tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601540035}'
: 1601540722:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1601540741:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a4", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["user_3","user3@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Female","Ha Noi"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","google"]],"at":1601337600}'
: 1601540819:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1601540823:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a4", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["user_3","user3@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Female","Ha Noi"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","google"]],"at":1601337600}'
: 1601541093:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601541097:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id": "event-xxx","tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601540035}'
: 1601541626:0;git s
: 1601541636:0;git push origin develop
: 1601541802:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id": "event-x","tenant_id":1, "anonymous_id": "a3", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601540035}'
: 1601541822:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id": "event-x","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 7", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601540035}'
: 1601542514:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1601542604:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601542585}'
: 1601542663:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601542585}'
: 1601542993:0;clear
: 1601542995:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["user_1","user1@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Female","Ha Noi"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","google"]],"at":1601337600}'
: 1601543410:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a1", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["chile","chile@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","mailchim"]],"at":1601337605}'
: 1601543643:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601543496}'
: 1601543742:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601543691}'
: 1601544113:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601543691}'
: 1601544463:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6068
: 1601544568:0;telnet [200~10.110.1.5 6379
: 1601544579:0;telnet 10.110.1.5 6379
: 1601544606:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6068
: 1601544643:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1601545077:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1601545028"}'
: 1601545131:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1601545135:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1601545028"}'
: 1601545739:0;git s
: 1601545752:0;git cm "testing stream flow on server"
: 1601545755:0;git a .
: 1601545758:0;git cm "testing stream flow on server"
: 1601545762:0;git push origin develop
: 1601549878:0;faust -A prile.workflows.profile_update.app send "profile-updated"  '{"tenant_id":1, "anonymous_id": "a2", "identity_keys":["user_id", "email","facebook_id"], "identity_vals" : ["chile","chile@gmail.com","KHK23"], "str_properties_keys":["gender","city"],"str_properties_vals":["Male","Ho Chi Minh"],"num_properties_keys":[],"num_properties_vals":[],"arr_properties_keys":["channels"],"arr_properties_vals":[["facebook","mailchim"]],"at":1601337705}'
: 1601549974:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a2", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601543791}'
: 1601550223:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601550212}'
: 1601550613:0;git s
: 1601550615:0;git a .
: 1601550659:0;git cm "update first, last activities api"
: 1601550662:0;git push origin develop
: 1601603221:0;git s
: 1601603331:0;cd /home/chile/Documents/pem
: 1601603334:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601603394:0;docker-compose up -d
: 1601603407:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601605029:0;faust -A prile.workflows.eventify_events.app worker -l info -p 6066
: 1601605196:0;faust -A prile.workflows.eventify_events.app send "eventify_event_topic"  '{"id":"event_1234","tenant_id":1, "anonymous_id": "a1", "event_name": "App Uninstalled", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency", "test_str"],"str_properties_vals":["VND","str_val"],"num_properties_keys":["total_value","float_key"],"num_properties_vals":[64000,123.12345678],"arr_properties_keys":["arr_test"],"arr_properties_vals":[["v1","v2","v3","v4"]],"at":1601543691}'
: 1601608629:0;git s
: 1601608631:0;git a .
: 1601608647:0;git cm "return all properties not filter"
: 1601611308:0;git s
: 1601611628:0;kubectl get po | grep event-processing
: 1601611688:0;kubectl logs -f event-processing-66dd464f45-9dm5n
: 1601611983:0;git push origin develop
: 1601614399:0;py.test
: 1601614808:0;clear
: 1601615046:0;cd common
: 1601615048:0;py.test
: 1601617885:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1601622422:0;git s
: 1601626432:0;git a .
: 1601626475:0;git cm "event schema change, added session_id and scope fields"
: 1601626481:0;git push origin develop
: 1601629983:0;git s
: 1601630360:0;clear
: 1601630380:0;cd tests/common
: 1601630381:0;ls
: 1601630402:0;test.py
: 1601630408:0;pytest.py
: 1601630411:0;pytest
: 1601633056:0;git s
: 1601633067:0;git push origin develop
: 1601633087:0;clear
: 1601633169:0;git stash save "testing data transformation"
: 1601633174:0;git checkout master
: 1601633178:0;git merge develop
: 1601633185:0;git pull origin master
: 1601633195:0;git push origin master
: 1601633204:0;git tree
: 1601634867:0;git s
: 1601634876:0;git a .
: 1601634904:0;git cm "switch kafka redis variable to consul"
: 1601634908:0;git push origin master
: 1601635395:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1601636270:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a5", "at":"1601636245"}'
: 1601863438:0;git s
: 1601863481:0;docker-compose up -d
: 1601865262:0;docker ps
: 1601865266:0;docker images
: 1601866619:0;docker pull odpi/apache-atlas
: 1601871580:0;docker images
: 1601871583:0;docker images --help
: 1601871597:0;docker rm -help
: 1601871605:0;docker --help
: 1601871637:0;docker rmi 195891401c29
: 1601871650:0;docker pull sburn/apache-atlas
: 1601871722:0;docker images
: 1601871742:0;docker run -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601871748:0;docker ps
: 1601871920:0;clear
: 1601871927:0;docker logs atlas
: 1601873280:0;git s
: 1601873295:0;git tree
: 1601873302:0;git a .
: 1601873317:0;git cm "change kafka redis config to consul"
: 1601873321:0;git push origin maste
: 1601873326:0;git push origin master
: 1601873391:0;git s
: 1601873394:0;git a 
: 1601873396:0;git a .
: 1601873399:0;git cm "change kafka redis config to consul"
: 1601873403:0;git s
: 1601873445:0;git push origin master
: 1601873450:0;git s
: 1601873452:0;git a .
: 1601873452:0;git s
: 1601873459:0;git cm "change kafka redis config to consul"
: 1601873464:0;git s
: 1601873524:0;git tree
: 1601873542:0;git s
: 1601873641:0;git push origin master
: 1601873647:0;git s
: 1601873659:0;cd ..
: 1601873664:0;git a .
: 1601873665:0;git s
: 1601873672:0;git cm "change kafka redis config to consul"
: 1601873673:0;git s
: 1601873679:0;git push origin master
: 1601881473:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1601881507:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601550212}'
: 1601881566:0;cd /home/chile/Documents/pem
: 1601881571:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1601881574:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1601881617:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"id":"event-123","tenant_id":1, "anonymous_id": "a1", "event_name": "Buy Xiaomi 123", "identity_keys":[], "identity_vals" : [], "str_properties_keys":["currency"],"str_properties_vals":["VND"],"num_properties_keys":["total_value"],"num_properties_vals":[64000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1601550212}'
: 1601881627:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1601881957:0;kubectl get po | grep conversion
: 1601881975:0;kubectl logs -f conversion-broadcast-597ddf6669-2cs6q
: 1601948279:0;docker run -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601948298:0;docker start -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601948307:0;docker --help
: 1601948320:0;docker restart -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601948360:0;docker images
: 1601948501:0;docker restart -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601948505:0;docker ps
: 1601948518:0;docker --help
: 1601948681:0;docker ps -a
: 1601948729:0;docker --help
: 1601948787:0;docker start -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601948812:0;docker start 71dddeb9a433
: 1601948816:0;docker ps
: 1601948849:0;docker stop $(docker ps -aq)
: 1601948865:0;docker ps
: 1601948870:0;docker ps -a
: 1601948901:0;docker start 71dddeb9a433
: 1601948906:0;docker ps
: 1601948938:0;docker stop 71dddeb9a433
: 1601949075:0;docker container start -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601949146:0;CCCCCCCCCCCCCCocker container start 
: 1601949160:0;af
: 1601949162:0;clear
: 1601949189:0;docker container start -it \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601949201:0;docker container start --help
: 1601949239:0;docker container start \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601949279:0;docker container start --detach-keys=first-start 
: 1601949283:0;docker ps
: 1601949290:0;docker ps -a
: 1601949299:0;docker container start --detach-keys=first-start 71dddeb9a433
: 1601949338:0;docker exec -ti atlas /opt/apache-atlas-2.1.0/bin/atlas_stop.py
: 1601949395:0;docker ps -a
: 1601949404:0;docker rm --help
: 1601949410:0;docker --help
: 1601949427:0;docker ps -a
: 1601949435:0;docker rm 71dddeb9a433
: 1601949438:0;docker ps -a
: 1601949452:0;docker ps -a | grep nginx
: 1601949461:0;docker run -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1601949465:0;docker ps
: 1601968960:0;npm i
: 1601969064:0;brew install node
: 1601969109:0;pacman -S nodejs npm
: 1601969117:0;pkg install node
: 1601969143:0;sudo apt install nodejs
: 1601969164:0;sudo apt install npm
: 1601969186:0;nodejs -v
: 1601969189:0;node -v
: 1601969193:0;npm i
: 1601969202:0;ls
: 1601969207:0;node study/shop-login.js
: 1601969244:0;npm config set ignore-scripts true
: 1601969249:0;npm i
: 1601969260:0;node study/shop-login.js
: 1601969270:0;npm config set PUPPETEER_SKIP_CHROMIUM_DOWNLOAD false
: 1601969272:0;npm config set ignore-scripts false
: 1601969285:0;npm i puppeteer
: 1601969294:0;node study/shop-login.js
: 1601969770:0;node study/shop-lo
: 1601969773:0;node study/shop-login.js
: 1601969837:0;which google-chrome
: 1601969848:0;which brave-browser
: 1601969868:0;node study/shop-login.js
: 1601970304:0;git s
: 1601974357:0;docker ps
: 1601974365:0;clear
: 1601978703:0;kubectl version
: 1601980158:0;clear
: 1601980187:0;docker version
: 1601980257:0;docker info
: 1601980354:0;docker container --help
: 1601980371:0;docker ps
: 1601980410:0;docker container ls -a
: 1601980437:0;docker --help
: 1601980462:0;docker container top 
: 1601980513:0;docker ps
: 1601980525:0;docker inspect 9cfc0536c14a
: 1601980568:0;docker container --help
: 1601980666:0;docker container run --help
: 1601980735:0;docker container start --help
: 1601981159:0;clear
: 1601981578:0;docker images
: 1601981592:0;docker rmi nginx
: 1601981615:0;docker images | nginx
: 1601981622:0;docker image ls
: 1601981634:0;docker --help
: 1601981642:0;docker rmi 08393e824c32
: 1601981663:0;docker container ls
: 1601981666:0;docker container --help
: 1601981689:0;docker ps
: 1601981692:0;docker ps -a
: 1601981708:0;docker ps -a | nginx
: 1601981716:0;docker ps -a
: 1601981721:0;docker ps -a | grep nginx
: 1601981741:0;docker rm 9e7df870bbf7 23257114a9fe 0d9b0c3a401f eb13533b592a
: 1601981744:0;docker ps -a
: 1601981752:0;docker image ls
: 1601981762:0;docker rmi 08393e824c32
: 1601981767:0;docker images
: 1601981834:0;docker pull nginx
: 1601981872:0;docker pull image nginx:1.11.9
: 1601981880:0;docker pull nginx:1.11.9
: 1601981893:0;docker ps
: 1601981896:0;docker images
: 1601982689:0;docker image ls
: 1601982736:0;docker history nginx:lastest
: 1601982744:0;docker images
: 1601982769:0;docker history 992e3b7be046
: 1602035683:0;docker-compose up -d
: 1602035706:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602035769:0;cd /home/chile/Documents/pem
: 1602035773:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602035919:0;git s
: 1602035921:0;git fetch
: 1602035926:0;git tree
: 1602035937:0;git s
: 1602036978:0;node -v
: 1602037140:0;sudo apt install -y chromium-browser
: 1602037193:0;docker stop $(docker ps -aq)
: 1602037216:0;sudo apt install -y chromium-browser
: 1602037282:0;which chromium-browser
: 1602037388:0;git clone https://github.com/primedata-ai/puppeteer-tools
: 1602037478:0;node shops/view-product.js
: 1602037489:0;npm install 
: 1602037545:0;node shops/view-product.js
: 1602037614:0;ls /usr/lib/chromium-browser
: 1602037635:0;node shops/view-product.js
: 1602037914:0;node -v
: 1602037968:0;npm
: 1602037971:0;nvm
: 1602037975:0;
: 1602037990:0;sudo apt update
: 1602038002:0;sudo apt install build-essential checkinstall libssl-dev
: 1602038020:0;curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.35.1/install.sh | bash
: 1602038038:0;nvm --version
: 1602038087:0;curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.35.1/install.sh | bash
: 1602038141:0;export NVM_DIR="$HOME/.nvm"\
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm\
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion\

: 1602038145:0;nvnm
: 1602038148:0;nvm
: 1602038152:0;nvm --version
: 1602038163:0;nvm ls
: 1602038170:0;nvm ls-remote
: 1602038225:0;nvm install 
: 1602038236:0;nvm install v12.18.4
: 1602038245:0;node -v
: 1602038276:0;node shops/view-product.js
: 1602038282:0;node -v
: 1602038396:0;sudo node -v
: 1602038417:0;npm cache clean -f
: 1602038489:0;sudo apt-get remove nodejs
: 1602038503:0;sudo apt-get purge nodejs
: 1602038516:0;sudo apt-get autoremove\

: 1602038527:0;node -v
: 1602038791:0;sudo mkdir -p /usr/local/lib/nodejs
: 1602038868:0;sudo tar -xJvf node-v12.18.4-linux-x64.tar.xz -C /usr/local/lib/nodejs
: 1602038942:0;export PATH=/usr/local/lib/nodejs/node-v12.18.4-linux-x64/bin:$PH
: 1602038943:0;clear
: 1602038961:0;cd
: 1602038995:0;nano ~/.profile
: 1602039065:0;sudo nano ~/.profile
: 1602039075:0;nano ~/.profile
: 1602039082:0;cd
: 1602039091:0;clear
: 1602039118:0;nano ~/.profile
: 1602039154:0;cat ~/.profile
: 1602039162:0;node -v
: 1602039175:0;. ~/.profile
: 1602039177:0;node -v
: 1602039234:0;npm install
: 1602039238:0;node install
: 1602039250:0;node -v
: 1602039252:0;node
: 1602039262:0;node -v
: 1602039275:0;. ~/.profile
: 1602039276:0;node
: 1602039289:0;. ~/.profile
: 1602039291:0;node -v
: 1602039300:0;npm install 
: 1602039309:0;node shops/view-product.js
: 1602043413:0;node shops/product_cart_view.js
: 1602043953:0;node shops/shop-signup.js
: 1602044055:0;clear
: 1602044090:0;node shops/shop-signup.js
: 1602045299:0;node shops/product_cart_view.js
: 1602050077:0;node shops/add_cart.js
: 1602060119:0;node shops/view_cart.js
: 1602060505:0;node shops/add_cart.js
: 1602062239:0;node shops/checkout_start.js
: 1602068119:0;node shops/add_cart.js
: 1602068566:0;node shops/flow.js
: 1602069449:0;node shops/-signup.js
: 1602069455:0;node shops/data-signup.json
: 1602069478:0;node shops/shop-signup.js
: 1602069506:0;node shops/flow.js
: 1602070200:0;node shops/shop-signup.js
: 1602070301:0;node shops/flow.js
: 1602070795:0;node shops/data-signup.json
: 1602070802:0;node shops/shop-signup.js
: 1602070820:0;node shops/flow.js
: 1602071068:0;git a .
: 1602071070:0;git s
: 1602071088:0;git cm "completed full flow events tracking"
: 1602071097:0;git push origin master
: 1602071104:0;git push origin main
: 1602071114:0;git push origin develop
: 1602071353:0;git push origin main
: 1602071590:0;git s
: 1602071597:0;git push origin main
: 1602119957:0;git s
: 1602119986:0;docker-compose up -d
: 1602120004:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602120075:0;cd /home/chile/Documents/pem
: 1602120110:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602120144:0;git a .
: 1602120221:0;git cm "user activity api back to pre-define properties"
: 1602120232:0;git pull
: 1602120240:0;git push origin master
: 1602120250:0;git checkout develop
: 1602120254:0;git merge master
: 1602120261:0;git pull
: 1602120269:0;git pull origin develop
: 1602120275:0;git tree
: 1602125888:0;git s
: 1602130519:0;clear
: 1602207013:0;docker-compose up -d
: 1602207043:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602207105:0;cd /home/chile/Documents/pem
: 1602207109:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602207154:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602207169:0;docker-compose up -d
: 1602207175:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602209429:0;docker ps
: 1602209450:0;docker stop $(docker ps -aq)
: 1602209471:0;docker-compose up -d
: 1602209477:0;ls
: 1602209479:0;clear
: 1602209482:0;docker ps
: 1602209487:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602213271:0;git s
: 1602213275:0;git a .
: 1602213339:0;git cm "release campaign revenue uplift api"
: 1602213343:0;git push origin develop
: 1602214387:0;git s
: 1602221465:0;git a .
: 1602221532:0;git cm "mofified how to get avg revenue per user: use segment size not num distict users"
: 1602221539:0;git push origin develop
: 1602224117:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602238160:0;docker run -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1602238167:0;docker ps
: 1602238170:0;docker ps -a
: 1602238178:0;docker ps -a | grep alats
: 1602238181:0;docker ps -a | grep atlas
: 1602238187:0;docker rm 9cfc0536c14a
: 1602238215:0;docker run -d \\
    -p 21000:21000 \\
    --name atlas \\
    sburn/apache-atlas \\
    /opt/apache-atlas-2.1.0/bin/atlas_start.py
: 1602238232:0;docker ps
: 1602298705:0;cd /home/chile/Documents/pem
: 1602298707:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602299806:0;docker-compose up -d
: 1602299811:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602303717:0;docker ps
: 1602303724:0;clear
: 1602304201:0;docker stop $(docker ps -aq)
: 1602304254:0;docker images
: 1602304281:0;docker pull mongo
: 1602304324:0;docker ps
: 1602304346:0;docker run --name mongo -d mongo
: 1602304351:0;docker ps
: 1602304357:0;docker top mongo
: 1602304423:0;ps aux
: 1602304429:0;ps aux | mongo
: 1602304445:0;docker top mongo
: 1602304457:0;ps aux | grep mongo
: 1602304467:0;ps aux | grep pycharm
: 1602304617:0;docker stop mongo
: 1602304620:0;docker ps
: 1602304628:0;docker top mongo
: 1602304637:0;ps aux | grep mong
: 1602304639:0;ps aux | grep mongo
: 1602305086:0;clear
: 1602305149:0;docker run nginx --name nginx -d -p 80:80
: 1602305218:0;docker container run --name webhost -d -p 80:80 nginx
: 1602305231:0;docker container run --name webhost -d -p 81:81 nginx
: 1602305246:0;docker ps
: 1602305248:0;docker ls -a
: 1602305253:0;docker ps -a
: 1602305272:0;docker container rm webhost
: 1602305277:0;docker ps -a
: 1602305323:0;docker container run --name webhost -d --p 81:80 nginx 
: 1602305330:0;docker container run --name webhost -d --port 81:80 nginx 
: 1602305343:0;docker container run --help
: 1602305372:0;docker container run --name webhost -p 81:80 -d nginx
: 1602305374:0;docker ps
: 1602305443:0;docker container run --name mysql -d -p 3306:3306 --env MYSQL_RANDOM_ROOT_PASSWORD=yes
: 1602305453:0;docker container run --name mysql -d -p 3306:3306 --env MYSQL_RANDOM_ROOT_PASSWORD=yes mysql
: 1602305465:0;docker container rm mysql
: 1602305502:0;docker container run mysql --name mysql -d -p 3306:3306 --env MYSQL_RANDOM_ROOT_PASSWORD=yes
: 1602305531:0;docker ps
: 1602305581:0;docker rm httpd
: 1602305591:0;docker ps -a | grep http
: 1602305655:0;docker container run --name httpd -d -p 8080:80 httpd
: 1602305657:0;docker ps
: 1602305670:0;docker container run --help
: 1602305760:0;docker container run --name mysql -d -p 3306:3306 mysql -e MYSQL_RANDOM_ROOT_PASSWORD=yres
: 1602305765:0;docker container run --name mysql -d -p 3306:3306 mysql -e MYSQL_RANDOM_ROOT_PASSWORD=yes
: 1602305773:0;docker ps
: 1602305783:0;clear
: 1602305790:0;docker container run --name mysql -d -p 3306:3306 mysql -e MYSQL_RANDOM_ROOT_PASSWORD=yes
: 1602305799:0;docker rm mysql
: 1602305801:0;docker ps
: 1602305807:0;docker ps -a | grep mysql
: 1602305822:0;docker container rm mysql
: 1602305832:0;docker container rm modest_morse
: 1602305834:0;docker ps
: 1602305902:0;docker container run --name mysql -d -p 3306:3306 -e  MYSQL_RANDOM_ROOT_PASSWORD=yes mysql
: 1602305905:0;docker ps
: 1602305920:0;docker container log mysql
: 1602305922:0;docker container logs mysql
: 1602306185:0;curl localhost:8080
: 1602306189:0;curl localhost:80
: 1602306201:0;clear
: 1602306203:0;docker ps
: 1602306217:0;curl localhost:3306
: 1602306242:0;echo localhost
: 1602306254:0;echo $localhost
: 1602306412:0;docker ps
: 1602306431:0;docker stop cd9fdc8bfce4 d3ed35e35c96 c4f69364984f
: 1602306437:0;docker ps -a
: 1602306438:0;clear
: 1602306451:0;docker container ls -a
: 1602307227:0;docker container stast
: 1602307243:0;docker container stats 
: 1602307254:0;docke ls
: 1602307261:0;docker container stats 
: 1602307765:0;docker --help
: 1602307781:0;docker start mysql
: 1602307790:0;docker start nginx
: 1602307797:0;docker start webhost
: 1602307800:0;docker ps
: 1602307807:0;docker --help
: 1602307823:0;docker stats mysql
: 1602308176:0;docker ps
: 1602308202:0;docker container run -it --name proxy nginx bash
: 1602308216:0;docker ps
: 1602310082:0;clear
: 1602310178:0;docker ps
: 1602310190:0;docker container port webhost
: 1602314497:0;docker network ls
: 1602314515:0;docker network inspect
: 1602314737:0;docker ps
: 1602314742:0;docker network ls
: 1602314751:0;docker inspect bridge
: 1602315126:0;docker-compose up -d
: 1602315137:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602317502:0;docker stop $(docker ps -aq)
: 1602466304:0;docker-compose up -d
: 1602466314:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602466340:0;cd /home/chile/Documents/pem
: 1602466343:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602466386:0;git s
: 1602466395:0;git a .
: 1602466396:0;git s
: 1602466416:0;git cm "get campaign trending metrics api"
: 1602466422:0;git push origin develop
: 1602466434:0;git checkout master
: 1602466445:0;git pull origin master
: 1602466462:0;git merge develop
: 1602466493:0;git tree
: 1602466548:0;git push origin master
: 1602466557:0;git tree
: 1602466652:0;git push origin master
: 1602467452:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602471170:0;git s
: 1602471187:0;git a .
: 1602471198:0;git cm "edited format time range"
: 1602471213:0;git push origin master
: 1602472103:0;git a .
: 1602472112:0;git cm "rename campaign to campaignName"
: 1602472115:0;git push origin master
: 1602473918:0;git a .
: 1602473927:0;git cm "active baseline api"
: 1602473934:0;git push origin master
: 1602474336:0;clear
: 1602474342:0;docker ps
: 1602474348:0;docker network ls
: 1602474404:0;docker network --help
: 1602474423:0;docker network inspect my_app_net
: 1602474470:0;docker container run -d --name my_nginx --network my_app_net nginx
: 1602474528:0;docker network inspect my_app_net
: 1602474624:0;docker container exec -it my_nginx ping new_nginx
: 1602474639:0;docker ps
: 1602474854:0;docker --help
: 1602474865:0;docker container --help
: 1602474886:0;docker --help | grep network
: 1602474900:0;docker container --network --help
: 1602474933:0;docker container run -d -name new_nginx --network my_app_net new_nginx
: 1602474948:0;docker container run -d --name new_nginx --network my_app_net new_nginx
: 1602474963:0;docker container run -d --name new_nginx --network my_app_net nginx
: 1602474966:0;docker ps
: 1602474970:0;docker ps | grep nginx
: 1602474992:0;docker network ls
: 1602475002:0;docker network inspect my_app_net
: 1602475059:0;docker container exec -it my_nginx ping new_nginx
: 1602475100:0;docker ping --help
: 1602475125:0;docker container exec -it my_nginx ping new_nginx
: 1602475129:0;docker network inspect my_app_net
: 1602475647:0;docker network ls
: 1602477015:0;docker container exec -it my_nginx ping new_nginx
: 1602477567:0;docker container create --help
: 1602478161:0;clear
: 1602478335:0;docker container run --rm -it centos:7 bash
: 1602478443:0;docker ps
: 1602478506:0;docker container run -it --rm ubuntu:14.04 bash
: 1602482799:0;docker ps
: 1602482985:0;clear
: 1602483120:0;docker network ls
: 1602483149:0;docker container run --help
: 1602483167:0;docker container run --help | grep --net
: 1602483172:0;docker container run --help 
: 1602483257:0;docker container run -d --network dude 
: 1602483277:0;docker container run -d --network dude --network-alias search elasticsearch:2
: 1602483316:0;docker ps
: 1602483333:0;docker container run -d --network dude --network-alias search elasticsearch:2
: 1602483343:0;docker ps
: 1602483358:0;docker stop 940d0730f65c
: 1602483360:0;docker rm 940d0730f65c
: 1602483365:0;docker ps
: 1602484172:0;docker stop a506f6777de6 390fed93559c
: 1602484177:0;docker rm a506f6777de6 390fed93559c
: 1602484180:0;docker ps
: 1602484198:0;docker stop 07fe40844f3f 0e9df22b2bb1 ff7fbdcd7339
: 1602484205:0;docker ps
: 1602484465:0;docker images 
: 1602484543:0;docker history nginx:latest
: 1602485801:0;git s
: 1602485957:0;kubectl port-forward svc/consul-ui 8501:80
: 1602488513:0;git a .
: 1602488527:0;git cm "add get campaign filter api"
: 1602488532:0;git push origin master
: 1602492101:0;docker image tag --help
: 1602492137:0;docker image ls
: 1602492161:0;clear
: 1602492192:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1602492197:0;clear
: 1602492200:0;docker image ls
: 1602493142:0;docker pull mysql/mysql-server
: 1602493160:0;docker image ls
: 1602494043:0;docker image tag --help
: 1602494217:0;docker image tag nginx chile/nginx
: 1602494223:0;docker image ls
: 1602494254:0;docker image push chile/nginx
: 1602494289:0;docker login
: 1602494297:0;docker image push chile/nginx
: 1602494338:0;docker image push chilevan74/nginx
: 1602494369:0;docker image tag nginx chilevan74/nginx
: 1602494372:0;docker images
: 1602494379:0;docker image --help
: 1602494445:0;docker image push chilevan74/nginx
: 1602494518:0;cat .docker/config.json
: 1602494527:0;docker login
: 1602494551:0;cat /home/chile/.docker/config.json
: 1602494721:0;docker image push chilevan74/nginx
: 1602495985:0;docker run --rm -it redis
: 1602496684:0;clear
: 1602501014:0;docker version
: 1602501289:0;docker run hello-world
: 1602502161:0;docker ps
: 1602502563:0;docker ps -a
: 1602502583:0;docker ps -a | grep hello
: 1602502591:0;docker rm 784bf3c3e071
: 1602502599:0;docker create hello-world
: 1602502601:0;docker ps
: 1602502608:0;docker ps -a | grep hello
: 1602502720:0;docker start --help
: 1602502732:0;docker ps
: 1602560659:0;git s
: 1602560674:0;git checkout master
: 1602560681:0;git pull origin master
: 1602560690:0;git checkout develop
: 1602560693:0;git merge master
: 1602560738:0;git 
: 1602560740:0;git tree
: 1602572689:0;docker-compose up -d
: 1602572702:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602580134:0;git clone https://github.com/levanchi74/Udemy_Complete_Tensorflow_2_and_Keras_Deep_Learning_Bootcamp.git
: 1602584492:0;pip3 instal -r requirements.txt
: 1602584501:0;pip3 install -r requirements.txt
: 1602590338:0;git s
: 1602590340:0;git a .
: 1602590686:0;git s
: 1602590691:0;git a .
: 1602590822:0;git cm "refactor: event campaign engagement stream, use pandas"
: 1602590873:0;git push origin develop
: 1602639724:0;docker-compose up -d
: 1602639732:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1602641444:0;faust -A prile.workflows.events_campaign_engagement.app worker -l info -p
: 1602641460:0;faust -A prile.workflows.events_campaign_engagement.app worker -l info
: 1602641515:0;cd /home/chile/Documents/pem
: 1602641522:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602641530:0;faust -A prile.workflows.events_campaign_engagement.app worker -l info
: 1602642381:0;git s
: 1602642382:0;git a .
: 1602642497:0;git cm "refine events campaign engagement stream, use a df object"
: 1602642502:0;git push origin develop
: 1602649201:0;faust -A prile.workflows.events_campaign_engagement.app worker -l info
: 1602649206:0;clear
: 1602649322:0;docker ps
: 1602649445:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1602649613:0;ping localhost
: 1602649622:0;ping localhost:9092
: 1602649625:0;ping localhost 9092
: 1602649687:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6067
: 1602649789:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a5", "at":"1601636245"}'
: 1602649882:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6067
: 1602649909:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a5", "at":"1601636245"}'
: 1602649961:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6067
: 1602649988:0;clear
: 1602650132:0;faust -A prile.workflows.events_campaign_engagement.app worker -l info
: 1602650544:0;docker --version
: 1602650718:0;git checkout master
: 1602650723:0;git merge develop
: 1602650730:0;git s
: 1602650744:0;git a .
: 1602651119:0;git s
: 1602651131:0;git cm "remove eventtify event process"
: 1602651135:0;git push origin develop
: 1602651234:0;git checkout master
: 1602651239:0;git s
: 1602651264:0;git stash save "flatten json before use pandas"
: 1602651269:0;git s
: 1602651282:0;git checkout master
: 1602651283:0;git tree
: 1602653214:0;docker ps
: 1602658945:0;clear
: 1602658958:0;git s
: 1602658961:0;git a .
: 1602658973:0;git cm "update readme how to run project"
: 1602658981:0;git push origin master
: 1602658996:0;git tree
: 1602659016:0;git pull origin master
: 1602659096:0;git tree
: 1602659180:0;git pull origin master
: 1602659188:0;git tree
: 1602659289:0;git push origin master
: 1602659297:0;git tree
: 1602674503:0;git s
: 1602686244:0;docker ps
: 1602686761:0;docker run --name redis 
: 1602686778:0;docker container run --name redis -d redis
: 1602686781:0;docekr ps
: 1602686783:0;docker ps
: 1602686802:0;docker exec -it redis redis-cli
: 1602686840:0;docker ps
: 1602688327:0;docker exec -it redis bash
: 1602688363:0;docker ps
: 1602688372:0;docker exec -it redis bash
: 1602688421:0;docker run --name redis_c redis
: 1602688430:0;docker run --name -d redis_c redis
: 1602688443:0;docker run --name redis_c -d redis
: 1602688455:0;docker stop redis_c
: 1602688461:0;docker rm redis_c
: 1602688464:0;docker ps 
: 1602688470:0;docker ls -a
: 1602688474:0;docker ps -a
: 1602688479:0;clear
: 1602688502:0;docker run --name redis_c -d redis
: 1602688505:0;docker ps
: 1602688529:0;docker exec -it redis_c 
: 1602688552:0;docker container exec --help
: 1602688572:0;docker exec -it redis_c bash
: 1602726215:0;docker build .
: 1602726230:0;docker ps
: 1602726239:0;docker images | grep 0dc70ca4aea6
: 1602726245:0;docker images
: 1602726293:0;docker --help | grep buld
: 1602726296:0;docker --help | grep build
: 1602727599:0;docker image inspect redis
: 1602728826:0;git s
: 1602728827:0;git a .
: 1602729279:0;git cm "split flow save data of event stream"
: 1602729283:0;git push origin master
: 1602732214:0;cd /home/chile/Documents/pem
: 1602732226:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602733932:0;git s
: 1602733943:0;git tree
: 1602737805:0;ls
: 1602737809:0;docker build .
: 1602737822:0;docker run 76679a450311
: 1602737825:0;docker ps
: 1602737923:0;docker build .
: 1602737930:0;docker run 64a9e95be750
: 1602737960:0;docker build
: 1602737961:0;docker build .
: 1602737967:0;docker run 93b1887939e5
: 1602738305:0;docker build -t chile/redis:latest
: 1602738320:0;docker build -t chile/redis:latest .
: 1602738324:0;docker images
: 1602738343:0;docker images chile/redis
: 1602738346:0;clear
: 1602741116:0;kubectl get po | grep event-processing
: 1602741295:0;kubectl get po | grep segment_user_update
: 1602741301:0;kubectl get po | grep segment_users_update
: 1602741307:0;kubectl get po
: 1602741321:0;kubectl get po | grep segments-users-update
: 1602741365:0;kubectl get logs -f segments-users-update-5cf96779cb-r6rcc
: 1602741504:0;git s
: 1602741509:0;git cm .
: 1602741517:0;git a
: 1602741519:0;git s
: 1602741520:0;git a .
: 1602741530:0;git cm "prepare for test data sample"
: 1602741534:0;git push origin master
: 1602744957:0;git a .
: 1602744972:0;git cm "prepare for test data sample: rename topic"
: 1602744976:0;git push origin master
: 1602745108:0;git a .
: 1602745110:0;git cm "prepare for test data sample: rename topic"
: 1602745112:0;git push origin master
: 1602745138:0;git a .
: 1602745140:0;git cm "prepare for test data sample: rename topic"
: 1602745141:0;git push origin master
: 1602745548:0;git a .
: 1602745551:0;git cm "prepare for test data sample: rename topic"
: 1602745554:0;git push origin master
: 1602745759:0;kubectl get po | grep profile
: 1602745774:0;kubectl logs -f profile-update-5c974ff8d-hvlj2
: 1602745820:0;kubectl get po | conversion
: 1602745826:0;kubectl get po
: 1602745838:0;kubectl get po | conversion
: 1602745900:0;kubectl get po | profile
: 1602745921:0;kubectl get po | grep conversion
: 1602745931:0;kubectl get po | grep profile
: 1602745949:0;kubectl logs -f conversion-broadcast-d5fb447f9-45nkm
: 1602745972:0;kubectl get po | grep segmen
: 1602746003:0;kubectl logs -f segments-users-update-7b69456cfb-d9mpx
: 1602746248:0;kubectl logs -f profile-update-5c974ff8d-hvlj2
: 1602746933:0;kubectl logs -f conversion-broadcast-d5fb447f9-45nkm
: 1602746937:0;kubectl logs -f segments-users-update-7b69456cfb-d9mpx
: 1602747188:0;cd ..
: 1602747189:0;ls
: 1602747206:0;cd ..
: 1602747207:0;ls
: 1602747210:0;cd PrimeData
: 1602747211:0;s
: 1602747211:0;ls
: 1602747214:0;cd puppeteer-tools
: 1602747214:0;ls
: 1602747357:0;node -v
: 1602747363:0;node shops/shop-
: 1602747367:0;node shops/shop-signup.js
: 1602747652:0;node shops/flow.js
: 1602749967:0;node shops/shop-signup.js
: 1602750575:0;node shops/shop-signup
: 1602750820:0;kubectl logs -f profile-update-5c974ff8d-hvlj2
: 1602751318:0;node shops/shop-signup
: 1602751405:0;history | grep openvpn
: 1602752259:0;node shops/shop-signup
: 1602752570:0;node shops/flow.js
: 1602752880:0;node shops/shop-signup.js
: 1602753588:0;history | grep openvpn
: 1602753595:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602753731:0;node shops/shop-signup.js
: 1602755326:0;tar -xvf kafka-2.6.0-src.tgz
: 1602755332:0;cd kafka-2.6.0-src
: 1602755333:0;ls
: 1602755334:0;cd bin
: 1602755335:0;ls
: 1602755474:0;./kafka-console-consumer.sh --help
: 1602755478:0;./kafka-console-consumer.sh -help
: 1602755494:0;[200~./kafka-console-consumer.sh --bootstrap-server  \BC10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094 \BD --topic profile-updated --from-beginning~
: 1602755497:0;./kafka-console-consumer.sh --bootstrap-server  \BC10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094 \BD --topic profile-updated --from-beginning
: 1602755523:0;./kafka-console-consumer.sh --bootstrap-server "10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094" --topic profile-updated --from-beginning
: 1602755542:0;./gradlew jar -PscalaVersion=2.13.2
: 1602755560:0;./kafka-console-consumer.sh --bootstrap-server "10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094" --topic profile-updated --from-beginning
: 1602755596:0;ls
: 1602755614:0;./kafka-console-consumer.sh --help
: 1602755626:0;ls
: 1602755627:0;cd ..
: 1602755628:0;ls
: 1602755726:0;tar -xzf kafka_2.13-2.6.0.tgz
: 1602755742:0;cd kafka_2.13-2.6.0
: 1602755799:0;./kafka-console-consumer.sh --bootstrap-server  \BC10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094 \BD --topic profile-updated --from-beginning
: 1602755805:0;ls
: 1602755808:0;cd bin
: 1602755808:0;ls
: 1602755811:0;./kafka-console-consumer.sh --bootstrap-server  \BC10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094 \BD --topic profile-updated --from-beginning
: 1602755835:0;java
: 1602755838:0;java -version
: 1602755856:0;docker ps 
: 1602755879:0;docker-compose up -d
: 1602755885:0;ls
: 1602755887:0;docker ps 
: 1602755915:0;docker exec -it 03bfe90be2ea /bin/bash
: 1602755919:0;docker exec -it 03bfe90be2ea /bin/sh
: 1602755929:0;docker ps | grep kafka
: 1602755936:0;docker-compose up -d
: 1602755941:0;docker ps | grep kafka
: 1602755954:0;docker exec -it 03bfe90be2ea /bin/sh
: 1602756126:0;kubectl logs -f profile-update-5c974ff8d-hvlj2
: 1602760270:0;node shops/shop-signup.js
: 1602770785:0;git s
: 1602771096:0;history
: 1602771233:0;history --help
: 1602771237:0;man history
: 1602771254:0;history
: 1602771415:0;cd /home/chile/Documents/pem
: 1602771419:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602771475:0;docker ps
: 1602771493:0;docker-compose up -d
: 1602771508:0;docker ps
: 1602771579:0;docker ps | grep kafka
: 1602771585:0;docker-compose up -d
: 1602771597:0;docker ps | grep kafka
: 1602771611:0;docker exec -it 03bfe90be2ea bash
: 1602773631:0;faust -A prile.workflows.segments_users_update.app worker
: 1602773841:0;faust -A prile.workflows.segments_users_update.app send "segment_opt"  '{"tenant_id":1, "segment":"s1", "state": "in", "user":"a1", "at":"1601636300"}'
: 1602774292:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602774311:0;git s
: 1602774313:0;git a .
: 1602774344:0;git cm "move repo and model into segments users update workflow"
: 1602774349:0;git push origin master
: 1602774850:0;docker exec -it 03bfe90be2ea bash
: 1602812643:0;git s
: 1602813206:0;docker-compose up -d
: 1602813214:0;cd /home/chile/Documents/pem
: 1602813217:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602814826:0;docker ps
: 1602814831:0;docker ps | grep kafka
: 1602814841:0;docker-compose up -d
: 1602814845:0;docker ps | grep kafka
: 1602814860:0;docker exec -it 03bfe90be2ea bash
: 1602815461:0;node shops/shop-signup.js
: 1602815733:0;docker ps | grep kafka
: 1602815767:0;docker exec -it 03bfe90be2ea bash
: 1602815950:0;node shops/shop-signup.js
: 1602816522:0;docker ps
: 1602816531:0;docker ps./kafka-console-consumer.sh --bootstrap-server "10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094" --topic conversion-events --from-beginning
: 1602816539:0;docker ps | grep kafka
: 1602816560:0;docker exec -it 03bfe90be2ea bash
: 1602816633:0;kubectl get po | profile
: 1602816639:0;kubectl get po | grep profile
: 1602816659:0;kubectl get logs -f profile-update-5cb876cc96-f5ql2
: 1602816690:0;kubectl logs -f profile-update-5cb876cc96-f5ql2
: 1602817256:0;node shops/shop-signup.js
: 1602818160:0;git s
: 1602818756:0;git ls-files
: 1602818792:0;git s
: 1602819087:0;git a .
: 1602819104:0;git cm "prepare for data sample"
: 1602819109:0;git push origin masetr
: 1602819114:0;git push origin master
: 1602819498:0;clear
: 1602827206:0;docker ps
: 1602827218:0;docker exec -it 03bfe90be2ea bash
: 1602834579:0;pip3 install -r requirements.txt
: 1602901376:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602903702:0;docker-compose up -d
: 1602903716:0;docker ps
: 1602904802:0;git s
: 1602904809:0;git a .
: 1602904840:0;git cm "added get campaign data function return DataFrame"
: 1602904844:0;git pull
: 1602904901:0;git pull origin master
: 1602904912:0;git s
: 1602904915:0;git pull origin master
: 1602904925:0;git push origin master
: 1602915035:0;	docker-compose up -d
: 1602915049:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1602915273:0;pip3 install from prile.eventify.repository.campaigns import CampaignRepo
: 1602915281:0;pip3 install clickhouse_sqlalchemy
: 1602920971:0;docekr ps
: 1602920980:0;		docker-compose up -d
: 1602921026:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1603160558:1;docker ps
: 1603160569:0;docker ps | grep kafka
: 1603160583:0;docekr ps
: 1603160586:0;docker ps
: 1603160600:0;docker exec -it 03bfe90be2ea bash
: 1603244849:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1603244880:1;		docker-compose up -d
: 1603244828:3;git pull origin develop
: 1603247210:1;git a .
: 1603247212:0;git s
: 1603247224:0;git cm "edit path api campaign perforamance"
: 1603247228:5;git push origin develop
: 1603247410:0;git s
: 1603248061:0;git a .
: 1603248063:0;git s
: 1603248089:0;git cm "fixing... query parameter"
: 1603248093:6;git push origin develop
: 1603249049:3;git pull origin develop
: 1603250952:0;git a .
: 1603250956:3;git push origin develop
: 1603250962:0;git a .
: 1603250984:0;git cm "edit get filter kpi key val"
: 1603250988:3;git push origin develop
: 1603251001:20;git pull origin develop
: 1603251108:0;git s
: 1603251111:0;git a 
: 1603251113:0;git a .
: 1603251126:0;git cm "edit get dimentsion filter"
: 1603251129:6;git push origin develop
: 1603255969:0;git s
: 1603255972:0;git a .
: 1603256071:0;git cm "refactor get metric, kpi, filter name in tranformation"
: 1603256076:5;git push origin develop
: 1603256084:20;git tree
: 1603256552:0;git checkout master
: 1603256557:0;git merge develop
: 1603256567:4;git tree
: 1603256785:0;git s
: 1603256793:0;docker ps
: 1603247784:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1603289017:0;git s
: 1603289021:0;git checkout develop
: 1603289022:0;git s
: 1603293302:0;git a .
: 1603293344:0;git cm "edited events campaigns schema and convert campaign metric func to dict"
: 1603293356:0;git s
: 1603293363:3;git pull origin develop
: 1603293380:7;git push origin develop
: 1603296671:0;git s
: 1603296686:0;git a .
: 1603296716:0;git cm "exclude endpoint setting"
: 1603296758:0;git checkout user_activity_fixing
: 1603296763:0;git checkout -b user_activity_fixing
: 1603297439:0;git s
: 1603288999:4;		docker-compose up -d
: 1603288977:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1603342007:0;history 
: 1603342022:0;history | grep kubect
: 1603342374:0;ls
: 1603342384:0;cd Downloads
: 1603342385:0;ls
: 1603343666:0;kubectl config show
: 1603343670:0;kubectl config view
: 1603343686:1;telnet lb-apiserver.kubernetes.local 8443
: 1603343788:1;dig lb-apiserver.kubernetes.local
: 1603343841:2;ping 10.110.1.11
: 1603344334:0;kubectl config view
: 1603340462:0;docker ps
: 1603340466:0;docker exec -it 03bfe90be2ea bash
: 1603349215:0;docker ps
: 1603349220:0;docker exec -it 03bfe90be2ea bash
: 1603338896:0;docker ps
: 1603338905:0;docker exec -it 03bfe90be2ea bash
: 1603348990:1;docker ps
: 1603348999:0;docker exec -it 03bfe90be2ea bash
: 1603352320:0;./kafka-topics.sh --bootstrap-server "10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094" --list
: 1603352324:0;docker ps 
: 1603352334:0;docker exec -it 03bfe90be2ea bash
: 1603348545:0;docker ps
: 1603348556:0;docker exec -it 03bfe90be2ea bash
: 1603353466:0;kubectl get po
: 1603353470:0;kubectl get po | profile
: 1603353476:0;kubectl get po | grep profile
: 1603353508:0;kubectl get po | grep segment
: 1603353553:2;kubectl delete po profile-update-5c974ff8d-hvlj2
: 1603353565:8;kubectl delete po profile-update-5cb876cc96-f5ql2
: 1603353578:0;kubectl get po | grep profile
: 1603353614:9;kubectl edit deployment profile-update
: 1603353625:0;kubectl get po 
: 1603353631:0;kubectl get po  | grep profile
: 1603353657:0;kubectl describe deployment profile-update
: 1603356785:0;kubectl get po
: 1603356988:0;kubectl get po | grep profile
: 1603357041:417;kubectl logs -f profile-update-7bcdc77c84-mlkj8
: 1603426783:1;kubectl get po | grep conversion
: 1603426813:0;kubectl delete [200~conversion-broadcast-d5fb447f9-45nkm~
: 1603426824:0;kubectl delete conversion-broadcast-d5fb447f9-45nkm
: 1603426831:0;kubectl get po | grep conversion
: 1603428290:1;kubectl logs -f conversion-broadcast-5478c48978-65xh6
: 1603428302:0;kubectl get po
: 1603428310:0;kubectl get po | grep conver
: 1603428323:0;kubectl logs -f [200~conversion-broadcast-6455c876cb-gm2x7~
: 1603428328:0;kubectl logs -f [200~conversion-broadcast-6455c876cb-gm2x7
: 1603428346:0;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7
: 1603450509:0;kubectl get po | grep conversion
: 1603450521:0;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7
: 1603450934:0;kubectl get po | grep profile
: 1603450943:0;kubectl logs -f profile-update-7bcdc77c84-mlkj8
: 1603450991:0;kubectl get po | grep conver
: 1603451004:0;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7
: 1603418738:0;docker ps
: 1603418761:0;docker ps | grep kafka
: 1603418765:0;docker exec -it 03bfe90be2ea bash
: 1603449700:0;docker ps
: 1603449707:0;docker exec -it 03bfe90be2ea bash
: 1603508012:0;shutdown
: 1603508033:0;shutdown --help
: 1603508044:0;shutdown -r
: 1603508054:0;exit
: 1603609919:0;docker exec -it 03bfe90be2ea bash
: 1603609922:5;		docker-compose up -d
: 1603614346:0;git s
: 1603614371:0;git a .
: 1603614444:0;git cm "events_campaign schema change => fixed get campaign revenue api"
: 1603614451:13;git pull origin develop
: 1603614481:0;git s
: 1603614483:41;git tree
: 1603614531:6;git push origin develop
: 1603614549:11;git tree
: 1603614838:0;git checkout -b try_not_user_format
: 1603615596:0;git a .
: 1603615615:0;git cm "can not use param in select statement"
: 1603615621:0;git checkout develop
: 1603621657:0;git s
: 1603621660:0;git a .
: 1603621685:0;git cm "FILL DATE => refactor get total user by source scope"
: 1603625985:0;git a .
: 1603625989:0;git s
: 1603626026:0;git cm "FILL DATE => refactor get total user by segment time series"
: 1603626030:7;git push origin develop
: 1603626090:0;git checkout master
: 1603626094:4;git pull origin master
: 1603626102:0;git merge develop
: 1603626107:5;git push origin master
: 1603626114:2;git tree
: 1603626123:0;git checkout develop
: 1603609934:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1603609939:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1603680550:1;kubectl get po | segment
: 1603680554:0;kubectl get po | grep segment
: 1603680704:1;kubectl logs -f segments-users-update
: 1603680715:20;kubectl logs -f segments-users-update-797db66b66-d5245
: 1603680753:0;kubectl get po | grep profile
: 1603680763:0;kubectl logs -f profile-update-7bcdc77c84-mlkj8
: 1603702267:0;kubectl get po | grep segment
: 1603702452:238;kubectl logs -f segments-users-update-797db66b66-d5245
: 1603702697:0;kubectl get po | grep segment
: 1603702735:6;kubectl logs -f segments-users-update-5d94768b54-2nfmt
: 1603702743:0;kubectl get po | grep segment
: 1603702857:300;kubectl logs -f segments-users-update-5d94768b54-2nfmt
: 1603703411:1;kubectl get po | grep segment
: 1603705463:3;kubectl logs -f segments-users-update-777bf5dc7d-tgb9d
: 1603706438:0;kubectl get po 
: 1603706457:29;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7
: 1603706492:300;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7 | grep DCQ5YdxiIt4fs4fbxZq9Btn3Z9B
: 1603706908:0;kubectl get po | conversion
: 1603706923:0;kubectl get po
: 1603706940:300;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7
: 1603709531:1;kubectl get po | grep event-processing
: 1603709550:468;kubectl logs -f event-processing-demo-57d57949c9-xc9jm
: 1603682132:0;docker ps
: 1603682139:0;docker exec -it 03bfe90be2ea bash
: 1603766124:0;kubectl get po | grep conversion
: 1603766133:300;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7
: 1603772687:1;kubectl get po | grep segment-user
: 1603772692:1;kubectl get po | grep segmen
: 1603772703:5;kubectl logs -f segments-users-update-777bf5dc7d-tgb9d
: 1603772999:0;kubectl get po | segment
: 1603773004:0;kubectl get po | grep segment
: 1603773015:0;kubectl logs -f segments-users-update-6d9ffcffcb-8pwct
: 1603775329:0;docker ps
: 1603775334:0;docker exec -it 03bfe90be2ea bash
: 1603786023:0;docker ps
: 1603786030:0;docker exec -it 03bfe90be2ea bash
: 1603775406:1;kubectl get po | conversion
: 1603775413:0;kubectl get po | grep conversion
: 1603775421:300;kubectl logs -f conversion-broadcast-6455c876cb-gm2x7
: 1603776791:1;kubectl get po | profile
: 1603776795:0;kubectl get po | grep profile
: 1603777910:0;kubectl get profile
: 1603777916:0;kubectl get po profile
: 1603777927:0;kubectl get po
: 1603777978:7;kubectl delete po profile-update-5547b879d8-wlb9g
: 1603777988:1;kubectl get po
: 1603778007:1;kubectl get profile
: 1603778016:0;kubectl get po | grep profile
: 1603788276:0;clear
: 1603788281:1;kubectl get po 
: 1603790143:417;kubectl logs -f segments-users-update-5f99fc47c4-wwndp
: 1603775567:0;kubectl get po | profile
: 1603775571:0;kubectl get po | grep profile
: 1603775578:313;kubectl logs -f profile-update-7bcdc77c84-mlkj8
: 1603788382:0;clear
: 1603788465:0;kubectl get po
: 1603788481:306;kubectl logs -f conversion-broadcast-75b9cb8968-wh5fr
: 1603788557:0;kubectl get po
: 1603788582:0;kubectl get po | grep profile 
: 1603788596:300;kubectl logs -f profile-update-79f6d96b64-7glpz
: 1603814135:0;pycharm
: 1603814144:0;which pycharm-professional
: 1603814150:0;cd snap/bin
: 1603814156:0;cd /snap
: 1603814157:0;ls
: 1603814163:0;cd pycharm-professional
: 1603814163:0;ls
: 1603814166:0;cd current
: 1603814166:0;ls
: 1603814173:0;cd plugins
: 1603814173:0;ls
: 1603814187:0;ls | grep slide
: 1603814265:0;ls
: 1603814266:0;cd ..
: 1603814267:0;ls
: 1603814272:0;cd snap
: 1603814273:0;ls
: 1603814275:0;cd gui
: 1603814275:0;ls
: 1603814278:0;cd ..
: 1603814281:0;ls
: 1603814283:0;cd ..
: 1603814284:1;ls
: 1603814298:0;cd plugins
: 1603814298:0;ls
: 1603814308:0;cd re
: 1603814310:0;cd rest
: 1603814311:0;ls
: 1603814313:0;cd ..
: 1603814315:0;clear
: 1603814316:0;ls
: 1603814341:0;rm -R AngularJS
: 1603814596:0;which pycharm-professional
: 1603814606:27;sudo pycharm-professional
: 1603814795:1;sudo snap remove pycharm-professional
: 1603815023:0;which pycharm-proressional
: 1603815129:0;# sync; echo 1 > /proc/sys/vm/drop_caches
: 1603815138:0;# sync; echo 2 > /proc/sys/vm/drop_caches
: 1603815176:0;free && sync && echo 3 > /proc/sys/vm/drop_caches && free
: 1603815181:1;sudo free && sync && echo 3 > /proc/sys/vm/drop_caches && free
: 1603815297:0;cd ~/.local/share/JetBrains
: 1603815298:0;ls
: 1603815308:0;cd PyCharm2020.
: 1603815312:0;cd PyCharm2020.2
: 1603815312:0;ls
: 1603815331:0;rm -R slides-presenter
: 1603815333:0;ls
: 1603815395:0;cd ~/.local/share/JetBrains/PyCharm2020.2
: 1603815396:0;ls
: 1603815425:0;cd ~/.cache/JetBrains/PyCharm2020.2
: 1603815425:0;ls
: 1603815430:0;cd plugins
: 1603815431:0;ls
: 1603815452:0;cd ..
: 1603815452:0;ls
: 1603815457:0;cd caches
: 1603815457:0;ls
: 1603885547:0;docker ps
: 1603885563:0;docker exec -it 03bfe90be2ea bash
: 1603850151:1;kubectl get po
: 1603850167:300;kubectl logs -f conversion-broadcast-75b9cb8968-wh5fr
: 1603853844:78;kubectl port-forward svc/consul-ui 8501:80
: 1603853927:0;kubectl port-forward svc/consul-ui 8501:8501
: 1603853986:225;kubectl port-forward svc/consul-ui 8501:80
: 1603855782:0;kubectl get po | profile
: 1603855788:0;kubectl get po | grep profile
: 1603855800:10;kubectl logs -f profile-update-79f6d96b64-7glpz
: 1603858943:811;kubectl port-forward svc/consul-ui 8501:80
: 1603864886:0;kubectl get po | grep profile
: 1603865234:155;kubectl logs -f faust-profile-update-8457969bb4-wd6lt
: 1603865394:1;kubectl get po | grep conversion
: 1603868053:0;kubectl logs -f faust-conversion-broadcast-7d78576cf9-cfkmk
: 1603868057:0;kubectl get po | grep conversion
: 1603868062:0;faust-conversion-broadcast-585dd6655f-6shff
: 1603868076:300;kubectl logs -f  faust-conversion-broadcast-585dd6655f-6shff
: 1603874908:0;kubectl get po
: 1603874923:0;kubectl describe po unomi-595d47cb6d-zfmp4
: 1603874932:2;kubectl get po
: 1603874949:0;kubectl describe po meta-router-77974457b4-8gbx7
: 1603884519:0;kubectl get po segment
: 1603884526:0;kubectl get po | grep segment
: 1603884539:440;kubectl logs -f faust-segments-users-update-64b8769dfd-gq9pw
: 1603886290:1;kubectl get po | grep segment
: 1603886309:0;kubectl logs -f segments-users-update-57469888c4-xgwpq
: 1603896641:0;docker ps
: 1603896647:259;docker exec -it 03bfe90be2ea bash
: 1603898002:3;faust -A prile.workflows.profile_update.app send "profile-updated" '{"anonymous_id": "DCQQ9AmHfoGKLjKrlKljtb02zen", "tenant_id": 1, "identity_keys": [], "identity_vals": [], "str_properties_keys": ["lastVisit","gender","location_city"], "str_properties_vals": ["2020-10-20T02:14:38Z","Female", "Ha Noi"], "num_properties_keys": ["nbOfVisits", "firstVisit"], "num_properties_vals": [1, 1603160100000], "arr_properties_keys": ["channels"], "arr_properties_vals": [["google","facebook"]], "at": 1603896868}'
: 1603900968:0;docker ps
: 1603900980:0;docker exec -it 03bfe90be2ea bash
: 1603898365:2548;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1603905075:63;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1603905141:0;git a .
: 1603905158:0;git cm "missing await"
: 1603905609:2;git push origin develop
: 1603905614:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1603894182:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1603897997:2911;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1603900914:4;faust -A prile.workflows.profile_update.app send "profile-updated" '{"anonymous_id": "DCbYfmAi29A3Skobl46tuLfmQil", "tenant_id": 0, "identity_keys": [], "identity_vals": [], "str_properties_keys": ["lastVisit"], "str_properties_vals": ["2020-10-20T02:14:38Z"], "num_properties_keys": ["nbOfVisits", "firstVisit"], "num_properties_vals": [1, 1603160100000], "arr_properties_keys": [], "arr_properties_vals": [], "at": 1603900347}'
: 1603901189:12;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1603901240:507;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1603898411:0;docker ps
: 1603898417:0;docker exec -it 03bfe90be2ea bash
: 1603894364:1;		docker-compose up -d
: 1603894278:0;docker ps
: 1603894370:0;docker ps | grep kafka
: 1603894381:0;docker exec -it 03bfe90be2ea bash
: 1603894067:0;git s
: 1603895087:2;faust -A prile.workflows.segments_users_update.app send "segment-user-update"  '{"segment":"1jVMk40iodyvOukinjcN9BeSSSk","state":"segmentOptIn","user":"DCQP9Ckh0hBxL1W6IPJFjg21kgQ","at":1603894425,"tenant_id":1}\
\
'
: 1603898693:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events" '{"eventType":"checkout_completed","itemId":"DB06SZESUs5rEQ108zeg6Au1Voo","itemType":"event","persistent":true,"profileId":"DCQQ9AmHfoGKLjKrlKljtb02zen","properties":{"cart_id":"1","cart_subtotal_value":0,"country":"VI","coupon_added":false,"currency":"vnd","discount_value":0,"gender":"male","order_id":"1","payment_method":"COD","shipping_address":"vi","shipping_cost":0,"shipping_country":"VI","shipping_state":"vi","shipping_zipcode":"70000","total_value":30},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","sendAt":1603777191883,"sessionId":"fe5fd438-fdab-bf59-e1f0-8e773c0f1323","source":{"itemId":"https://weburnit.github.io/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://weburnit.github.io/","pageName":"Pullman Hotel Resorts - Saloniz Solution","pagePath":"/","referringURL":""}},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","version":null},"target":{"itemId":"/","itemType":"page","properties":{},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","version":null},"tenant_id":1,"timeStamp":1603584060,"version":null}'
: 1603898796:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events" '{"eventType":"checkout_completed","itemId":"DB06SZESUs5rEQ108zeg6Au1Voo","itemType":"event","persistent":true,"profileId":"DB80ga9Cn18JZM7t9A81w6g6SRo","properties":{"cart_id":"1","cart_subtotal_value":0,"country":"VI","coupon_added":false,"currency":"vnd","discount_value":0,"gender":"male","order_id":"1","payment_method":"COD","shipping_address":"vi","shipping_cost":0,"shipping_country":"VI","shipping_state":"vi","shipping_zipcode":"70000","total_value":30},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","sendAt":1603777191883,"sessionId":"fe5fd438-fdab-bf59-e1f0-8e773c0f1323","source":{"itemId":"https://weburnit.github.io/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://weburnit.github.io/","pageName":"Pullman Hotel Resorts - Saloniz Solution","pagePath":"/","referringURL":""}},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","version":null},"target":{"itemId":"/","itemType":"page","properties":{},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","version":null},"tenant_id":1,"timeStamp":1603584160,"version":null}'
: 1603898861:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events" '{"eventType":"checkout_completed","itemId":"DB06SZESUs5rEQ108zeg6Au1Voo","itemType":"event","persistent":true,"profileId":"DB80ga9Cn18JZM7t9A81w6g6SRo","properties":{"cart_id":"1","cart_subtotal_value":0,"country":"VI","coupon_added":false,"currency":"vnd","discount_value":0,"gender":"male","order_id":"1","payment_method":"COD","shipping_address":"vi","shipping_cost":0,"shipping_country":"VI","shipping_state":"vi","shipping_zipcode":"70000","total_value":20},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","sendAt":1603777191883,"sessionId":"fe5fd438-fdab-bf59-e1f0-8e773c0f1323","source":{"itemId":"https://weburnit.github.io/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://weburnit.github.io/","pageName":"Pullman Hotel Resorts - Saloniz Solution","pagePath":"/","referringURL":""}},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","version":null},"target":{"itemId":"/","itemType":"page","properties":{},"scope":"JS-1iRNWBw2hNQTRQibnJeb8NTep7u","version":null},"tenant_id":1,"timeStamp":1603584260,"version":null}'
: 1603898907:0;git a .
: 1603898908:0;git s
: 1603898949:0;git cm "fixed bug import in workflow and prepare re-build develop"
: 1603898955:0;git checkout develop
: 1603898960:4;git pull origin
: 1603898969:4;git pull origin develop
: 1603898978:0;git merge api
: 1603898984:7;git push origin develop
: 1603898993:4;git tree
: 1603899418:0;gti s
: 1603899419:0;git s
: 1603899421:0;git a .
: 1603899428:0;git cm "rename app name"
: 1603899432:7;git push origin develop
: 1603899828:0;git a .
: 1603899847:0;git cm "edited ENV variable"
: 1603899850:6;git push origin develop
: 1603901306:3;faust -A prile.workflows.profile_update.app send "profile-updated" '{"anonymous_id":"DBXMHxUZxmV6mqVtwbZAaiC7wdc","tenant_id":1,"identity_keys":[],"identity_vals":[],"str_properties_keys":["lastVisit"],"str_properties_vals":["2020-10-15T09:45:03Z"],"num_properties_keys":["nbOfVisits","firstVisit"],"num_properties_vals":[1,1602755100000],"arr_properties_keys":[],"arr_properties_vals":[],"at":1602755103}'
: 1603901775:0;git a .
: 1603901827:0;git cm "stream-profile-update fixed identify is None"
: 1603901832:7;git push origin develop
: 1603902025:0;git s
: 1603902185:0;git a .
: 1603902191:0;git s
: 1603902199:0;git cm "rename config namespace"
: 1603902203:6;git push origin develop
: 1603903374:0;git a .
: 1603903450:0;git cm "stream-profile update: fixed at is nano second"
: 1603903453:7;git push origin develop
: 1603905007:0;git s .
: 1603905010:0;git a .
: 1603905023:0;git cm "expose get sample user by segment"
: 1603905026:7;git push origin develop
: 1603900157:28;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1603900238:2;faust -A prile.workflows.segments_users_update.app send "segment-user-update"  '{"tenant_id":1, "segment":"1jP08tvZXG9vJj7uJ4okEwCCLlE", "state": "segmentOptIn", "user":"DCQQ9AmHfoGKLjKrlKljtb02zen", "at":"1603584000"}'
: 1603900379:4;faust -A prile.workflows.segments_users_update.app send "segment-user-update"  '{"tenant_id":1, "segment":"1jP08tvZXG9vJj7uJ4okEwCCLlE", "state": "segmentOptIn", "user":"DCbYfmAi29A3Skobl46tuLfmQil", "at":"1603900347"}'
: 1603900566:0;git a .
: 1603900571:0;git cm "rename app name"
: 1603900575:7;git push origin develop
: 1603902674:0;docker ps
: 1603902681:0;docker exec -it 03bfe90be2ea bash
: 1603895121:0;kubectl get po | grep segment
: 1603895228:19;kubectl logs -f segments-users-update-57469888c4-xgwpq
: 1603895252:0;kubectl get po | grep faust
: 1603895257:1;kubectl get po | grep fast
: 1603895433:1;kubectl get po | grep segment
: 1603895446:1;kubectl delete segments-users-update-57469888c4-xgwpq
: 1603895463:42;kubectl delete po segments-users-update-57469888c4-xgwpq
: 1603895510:0;kubectl get po | grep segment
: 1603895560:0;kubectl get po | grep profile
: 1603895566:0;kubectl get po | grep conversion
: 1603895859:0;kubectl get po | grep segment
: 1603896094:135;ssh 10.110.1.4
: 1603896238:0;kubectl get po | grep event-processing
: 1603896248:0;kubectl get po | grep fast
: 1603896509:0;kubectl get po | grep event
: 1603896513:0;kubectl get po | grep event-pro
: 1603899218:1;kubectl get po | grep fast
: 1603899221:0;kubectl get po | grep faust
: 1603899233:0;kubectl get po | grep segment
: 1603899314:0;kubectl describe deploy segments-users-update-5487658b8b-s9kz8
: 1603899318:0;kubectl describe segments-users-update-5487658b8b-s9kz8
: 1603899658:0;kubectl get po | grep segment
: 1603899704:0;kubectl describe pods faust-segments-users-update-7d4fc98b46-cqsl7
: 1603899778:0;kubectl logs -f faust-segments-users-update-7d4fc98b46-cqsl7
: 1603900129:0;kubectl get po | grep segment
: 1603900139:0;kubectl get po | grep fast
: 1603900247:1;kubectl get po | grep faust
: 1603900393:188;kubectl logs -f faust-segments-users-update-f648fb646-tjpkg
: 1603900832:0;kubectl get po | grep faust
: 1603900931:122;kubectl logs -f faust-profile-update-55764fd64-xjj8l
: 1603902274:0;kubectl get po | grep faust
: 1603902360:3;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm
: 1603902380:0;kubectl get po | grep faust
: 1603903480:63;kubectl logs -f faust-profile-update-5465df89d6-t6l8m
: 1603903672:0;kubectl get po | grep faust
: 1603903705:2;kubectl logs -f faust-profile-update-56dd4bb768-kkp9t
: 1603903708:0;kubectl get po | grep faust
: 1603903716:0;faust-conversion-broadcast-dcf595bcf-2c8zm
: 1603903721:26;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm
: 1603903755:0;kubectl get po | grep faust
: 1603903762:248;kubectl logs -f faust-profile-update-56dd4bb768-kkp9t
: 1603936142:0;git s
: 1603936244:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1603936238:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1603944699:0;		docker-compose up -d
: 1603944688:0;docker ps
: 1603944735:0;docker exec -it 03bfe90be2ea bash
: 1603939320:0;git s
: 1603939324:0;git a .
: 1603939381:0;git cm "api-get sample user by segment-fix pros key"
: 1603939386:6;git push origin develop
: 1603940535:0;git s
: 1603940619:7;git tree
: 1603940740:0;git s
: 1603941254:0;git a .
: 1603941271:0;git cm "api-get sample user by segment fix pros key"
: 1603941275:6;git push origin develop
: 1603941533:0;git s
: 1603941614:0;git a .
: 1603941616:0;git cm "api-get sample user by segment fix pros key"
: 1603941622:6;git push origin develop
: 1603947830:0;git s
: 1603947847:0;git cm "fix how to calcul total user in segment"
: 1603947851:0;git a .
: 1603947854:0;git cm "fix how to calcul total user in segment"
: 1603947859:6;git push origin develop
: 1603951613:0;git s
: 1603951616:0;git a .
: 1603951672:0;git cm "api - segment analytics acquisition source fix pros key"
: 1603951674:0;git s
: 1603951678:6;git push origin develop
: 1603952722:0;gi ts
: 1603954422:0;git s
: 1603954543:0;git a .
: 1603954563:0;git cm "api - segment analytics total order fixed hard code key"
: 1603954568:6;git push origin develop
: 1603961966:0;git s
: 1603970575:0;git fetch origin/streaming
: 1603970580:4;git fetch origin streaming
: 1603970596:0;git checkout -b origin/streaming streaming
: 1603970608:0;git checkout -b origin streaming streaming
: 1603970635:0;git checkout -b streaming origin/streaming
: 1603970640:0;git s
: 1603970663:0;git a .
: 1603970676:0;git cm "rename field name in sql"
: 1603970681:0;git checkout -b streaming origin/streaming
: 1603970687:3;git tree
: 1603970695:0;git merge develop
: 1603953570:0;docker ps
: 1603953577:0;docker exec -it 03bfe90be2ea bash
: 1603936263:0;kubectl get po | grep faust
: 1603936281:4168;kubectl logs -f faust-segments-users-update-f648fb646-tjpkg
: 1603940461:0;kubectl get po | grep event-processing
: 1603940643:324;kubectl logs -f event-processing-55d749cd67-l4dxs
: 1603953167:0;clear
: 1603953171:0;kubectl get po | faust
: 1603953179:0;kubectl get po | grep faust
: 1603953199:0;kubectl logs -f | grep faust-conversion-broadcast-dcf595bcf-2c8zm
: 1603953228:238;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm | grep DCavCaog5eLSGFwi8f8mBes25iU
: 1603955596:467;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm
: 1603953270:0;kubectl get po | grep profile
: 1603953294:109;kubectl logs -f faust-profile-update-56dd4bb768-kkp9t | grep DCavCaog5eLSGFwi8f8mBes25iU
: 1603953520:1;kubectl get po | grep conversion
: 1603956015:0;kubectl get po | grep profile
: 1603956022:677;kubectl logs -f faust-profile-update-56dd4bb768-kkp9t
: 1603981447:1;		docker-compose up -d
: 1603982831:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1603985027:0;kubectl get po | grep faust
: 1603985039:4;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm
: 1603985051:117;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm | grep DCg5lymvV1UVegrVGyN1GQ5L9AK
: 1603985177:0;kubectl get po | grep faust
: 1603985199:328;kubectl logs -f faust-profile-update-56dd4bb768-kkp9t | grep DCg5lymvV1UVegrVGyN1GQ5L9AK
: 1604234685:0;git s
: 1604234690:2;git a .
: 1604234693:0;git cm 
: 1604234696:0;git s
: 1604234705:0;git cm "added java doc fpt"
: 1604234710:106;git push origin master
: 1604233810:209;git clone https://github.com/levanchi74/Java_Frehser.git
: 1604233308:0;kubectl get po | grep conversion
: 1604233315:4;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm
: 1604233328:301;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm | grep DCrvz9BLRkUA8ovG9BmwxpeGH5e
: 1604295799:1;docker ps
: 1604295804:0;docker exec -it 03bfe90be2ea bash
: 1604317634:0;./kafka-run-class.sh kafka.tools.GetOffsetShell --broker-list "10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094" --topic profile-updated
: 1604314269:1;kubectl get deployment 
: 1604314314:34;kubectl edit deployment faust-conversion-broadcast
: 1604314372:1;kubectl delete deployment faust-conversion-broadcast
: 1604314397:0;kubectl get po | grep faust
: 1604314417:0;kubectl delete deployment segments-users-update
: 1604314425:0;kubectl get po | grep faust
: 1604314460:0;kubectl delete deployment faust-profile-update-56dd4bb768-kkp9t
: 1604314469:1;kubectl delete deployment faust-profile-update
: 1604314477:0;kubectl get po | grep faust
: 1604314832:0;kubectl get po
: 1604314864:1;kubectl get po | grep data-rou
: 1604295619:0;kubectl get po | faust
: 1604295622:0;kubectl get po | grep faust
: 1604295640:21;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm
: 1604295665:300;kubectl logs -f faust-conversion-broadcast-dcf595bcf-2c8zm | grep DC1Gr7DX9AQx81vtqkss8YTzHhU
: 1604332859:0;docker ps
: 1604332864:0;docker exec -it 03bfe90be2ea bash
: 1604338840:1;kubectl get po | faust
: 1604338844:0;kubectl get po 
: 1604338851:0;kubectl get po | grep faust
: 1604368030:1;kubectl get po | faust
: 1604368035:0;kubectl get po | grep faust
: 1604368477:854;kubectl logs -f faust-conversion-broadcast-894d86bb7-gt972
: 1604369338:0;kubectl get deployment
: 1604369647:0;clear
: 1604370600:1;kubectl get po | grep faust 
: 1604370608:0;clear
: 1604372063:0;kubectl get po | grep faust 
: 1604372072:225;kubectl logs -f faust-conversion-broadcast-6ddcdb4bff-slnrz
: 1604398232:0;kubectl get po | grep faust
: 1604368549:1038;kubectl logs -f faust-profile-update-74599cc5c4-gprz6
: 1604369644:0;clear
: 1604372237:1;kubectl get deployment
: 1604372253:0;kubectl delete deployment faust-profile-update
: 1604372266:0;kubectl delete deployment faust-conversion-broadcast
: 1604367867:1;docker ps
: 1604367872:0;docker exec -it 03bfe90be2ea bash
: 1604405521:1;docker ps
: 1604405528:0;docker exec -it 03bfe90be2ea bash
: 1604368172:0;./kafka-console-consumer.sh --bootstrap-server "10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094" --topic profile-updated --offset 101800 --partition 0
: 1604368181:0;docker ps
: 1604368186:0;docker exec -it 03bfe90be2ea bash
: 1604405041:0;dasfasdf
: 1604405734:0;kubectl get po | grep faust
: 1604405740:0;kubectl get deployment
: 1604405757:0;kubectl delete deployment faust-segments-users-update
: 1604405760:0;kubectl get deployment
: 1604405836:0;kubectl get po | grep faust
: 1604405838:1;kubectl get po
: 1604415291:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1604415299:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1604415271:0;docker exec -it 03bfe90be2ea bash
: 1604415412:1;		docker-compose up -d
: 1604418398:0;git s
: 1604418400:0;git a .
: 1604418416:0;git cm "update sql schema to database folder"
: 1604418418:0;git s
: 1604453837:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1604455866:0;git status
: 1604474751:0;git s
: 1604474752:0;git a .
: 1604476727:0;git s
: 1604476762:0;git cm "fixxing.. profile update two event same time"
: 1604476975:0;git s
: 1604477001:0;git cm "added schema get user's ptrait metric"
: 1604477002:0;git a .
: 1604477004:0;git cm "added schema get user's ptrait metric"
: 1604477007:7;git push origin develop
: 1604481974:0;git a .
: 1604481982:0;git cm "expose user ptrait api"
: 1604481987:6;git push origin develop
: 1604482075:4;git pull origin develop
: 1604482088:2;git tree
: 1604487625:0;git s
: 1604487680:0;git cm "fix bug get total row not detect system events"
: 1604487681:0;git a 
: 1604487683:0;git a .
: 1604487685:0;git cm "fix bug get total row not detect system events"
: 1604487686:0;git s
: 1604487693:7;git push origin develop
: 1604456288:6;git tree
: 1604456298:6;git push origin develop
: 1604456306:0;git s
: 1604493220:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1604474709:20;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1604483213:4611;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1604487939:0;git s
: 1604487942:3;git tree
: 1604489924:0;git checkout -b profile_update_conversion
: 1604492735:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1604453961:1;		docker-compose up -d
: 1604453857:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1604454418:1;kubectl get po | faust
: 1604454423:0;kubectl get po | grep faust
: 1604454654:0;kubectl logs -f faust-segments-users-update-569bb9bf58-57n9h
: 1604454810:0;kubectl get po | grep faust
: 1604454816:506;kubectl logs -f faust-profile-update-7666db88c4-c7p2h
: 1604454551:1;kubectl get deployment 
: 1604454566:1;kubectl delete faust-segments-users-update
: 1604454574:0;kubectl delete deployment faust-segments-users-update
: 1604454851:0;kubectl get po | grep faust
: 1604454859:450;kubectl logs -f faust-conversion-broadcast-745d6b5c75-7bmn7
: 1604455648:0;kubectl get po | grep faust
: 1604455664:0;kubectl get deployment
: 1604455759:63;kubectl logs -f faust-segments-users-update-5c7dd8cf8b-xw7wh
: 1604455938:0;kubectl get deployment
: 1604455993:1;kubectl get po | grep faust
: 1604455996:0;clear
: 1604456010:0;kubectl get po | grep faust
: 1604456027:0;kubectl get deployment
: 1604456029:1;kubectl get po | grep faust
: 1604456040:8;kubectl logs -f faust-segments-users-update-8d6645f66-g8sqv
: 1604456050:1;kubectl get po | grep faust
: 1604456134:13;kubectl logs -f faust-segments-users-update-8d6645f66-g8sqv
: 1604456709:0;kubectl get po | grep faust
: 1604456717:737;kubectl logs -f faust-segments-users-update-57ffdbd4f8-qfv4k
: 1604457830:0;kubectl get deployment
: 1604457845:0;kubectl delete deployment faust-conversion-broadcast
: 1604457862:0;kubectl delete deployment faust-profile-update
: 1604487810:1;kubectl get po | grep faust
: 1604488106:0;kubectl get po | grep event
: 1604492569:0;kubectl get deployment
: 1604492591:0;kubectl delete faust-profile-update
: 1604492598:0;kubectl delete deployment faust-profile-update
: 1604492618:0;kubectl delete deployment faust-conversion-broadcast
: 1604493348:10;docker stop $(docker ps -aq)
: 1604500479:0;docker ps
: 1604500484:0;docker exec -it 03bfe90be2ea bash
: 1604500694:0;docker ps
: 1604500702:0;docker exec -it 03bfe90be2ea bash
: 1604500348:1;kubectl get po | grep faust
: 1604543121:0;git s
: 1604543125:0;git a .
: 1604543262:0;git cm "remove log process big data Vu push"
: 1604543268:7;git push origin profile_update_conversion
: 1604543299:0;git s
: 1604543300:4;git tree
: 1604579823:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1604542069:0;docker ps
: 1604542076:0;docker exec -it 03bfe90be2ea bash
: 1604541926:0;git s
: 1604541933:0;git a .
: 1604541948:0;git cm "added revenue and total order to ptraits"
: 1604541952:0;git checkout develop
: 1604541978:0;git checkout profile_update_conversion
: 1604556586:0;clear
: 1604541627:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1604556161:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-event"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | User's Blog,"pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545871308,"version":null}'
: 1604556217:0;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | User's Blog,"pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545871308,"version":null}'\
\
\
\
\
\

: 1604556219:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | Users Blog!","pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545871308,"version":null}'
: 1604556315:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | Users Blog!","pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545871309,"version":null}'
: 1604556583:0;clear
: 1604556638:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | Users Blog!","pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545871310,"version":null}'
: 1604556857:2;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | Users Blog!","pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545871410,"version":null}'
: 1604557325:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | Users Blog!","pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545871411,"version":null}'
: 1604557369:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | Users Blog!","pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545875440,"version":null}'
: 1604557403:3;faust -A prile.workflows.conversion_broadcast.app send "conversion-events"  '{"eventType":"checkout_completed","itemId":"DDEfT7Y3V0dEeQKpCSch7K15qjA","itemType":"event","persistent":true,"profileId":"DDEfSp3Gxr6swbztWP6NAmVSrq4","properties":{"cart_id":"kh496lz4_9335999366687935","cart_subtotal_value":92833,"coupon_added":true,"currency":"VND","discount_value":129205,"order_id":"kh496lz4_5790788966783749","payment_method":"CAST","shipping_address":"Japan","shipping_address_new":"Japan","shipping_cost":23206,"shipping_country":"Syria","shipping_state":"Indiana","shipping_zipcode":"368814","total_value":169169},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","sendAt":1604545871359,"sessionId":"e6d782f0-7255-8723-c424-5d64f1fea614","source":{"itemId":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{"attributes":[],"consentTypes":[],"interests":{},"pageInfo":{"destinationURL":"https://wp.primedata.ai/2020/11/04/wpsource-nguyen/","pageName":"WPSource-Nguyen | Users Blog!","pagePath":"/2020/11/04/wpsource-nguyen/","referringURL":""}},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"target":{"itemId":"/2020/11/04/wpsource-nguyen/","itemType":"page","properties":{},"scope":"JS-1jnzbSmvZgdVDn3ug9NVjyUGAhc","version":null},"tenant_id":1,"timeStamp":1604545875441,"version":null}'
: 1604579749:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1604541645:1;		docker-compose up -d
: 1604548245:0;git s
: 1604558346:0;git a .
: 1604558350:0;git s
: 1604558371:0;git cm "test profile udpate again"
: 1604558394:0;git checkout develop
: 1604558416:0;git checkout profile_update_conversion
: 1604558417:0;git s
: 1604558596:0;git checkout develop
: 1604558601:4;git pull origin develop
: 1604558634:6;git merge profile_update_conversion
: 1604558646:8;git tree
: 1604558657:7;git push origin develop
: 1604571269:0;git s
: 1604571270:0;git a .
: 1604571301:0;git cm "fixed profile update duplicate data"
: 1604577468:0;git s
: 1604577473:0;git a .
: 1604577499:0;git cm "removed profile entity"
: 1604577632:0;git s
: 1604578140:0;git checkout profile_update_conversion
: 1604578144:0;git merge develop
: 1604578147:0;git s
: 1604546306:0;docker ps
: 1604546312:0;docker exec -it 03bfe90be2ea bash
: 1604578770:0;docker ps
: 1604578790:0;docker exec -it efa7b517aa29 /bin/bash
: 1604541651:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1604541850:853;kubectl logs -f faust-profile-update-95ccc8f4d-qjzvt
: 1604542711:1;kubectl get deployment
: 1604542739:0;kubectl get deployment faust-profile-update
: 1604542752:0;kubectl delete deployment faust-profile-update
: 1604543083:1;kubectl get po | grep faust
: 1604543090:28;kubectl logs -f faust-conversion-broadcast-68cbbb57fc-2ltnt
: 1604544294:0;kubectl get po | grep faust
: 1604544302:68;kubectl logs -f faust-profile-update-7779676796-fr5dx
: 1604544376:1;kubectl get deployment
: 1604544390:0;kubectl delete deployment faust-profile-update
: 1604560717:0;kubectl get po | grep faust
: 1604560815:0;kubectl delete deployment faust-profile-update
: 1604560849:0;kubectl get po | grep faust
: 1604560885:1;kubectl get deployment
: 1604560896:0;kubectl delete deployment faust-conversion-broadcast
: 1604578734:0;kubectl get po | grep faust
: 1604579239:0;clear
: 1604579244:0;kubectl get po | grep faust
: 1604579693:225;kubectl logs -f faust-profile-update-58c7f99c7b-kjccb
: 1604579922:0;kubectl get po | grep faust
: 1604579939:0;kubectl logs -f faust-conversion-broadcast-6c98c78755-str67
: 1604579652:303;kubectl logs -f faust-segments-users-update-57ffdbd4f8-qfv4k
: 1604579960:0;kubectl get po | grep faust
: 1604579984:0;kubectl logs -f faust-profile-update-58c7f99c7b-kjccb
: 1604584816:1;kubectl get po | grep faust
: 1604584827:162;kubectl logs -f faust-profile-update-58c7f99c7b-kjccb
: 1604584995:0;kubectl get deployment
: 1604585125:0;kubectl delete deployment faust-profile-update
: 1604585130:0;kubectl get po | grep faust
: 1604586725:308;kubectl logs -f faust-segments-users-update-57ffdbd4f8-qfv4k
: 1604585388:0;kubectl get po | grep faust
: 1604588121:1949;kubectl logs -f faust-profile-update-6ff867b7c8-zg4tf
: 1604585448:0;kubectl get po | grep faust
: 1604588112:1945;kubectl logs -f faust-conversion-broadcast-5b6dcbf699-cdq5m
: 1604652322:1;kubectl get po 
: 1604629725:1;docker ps
: 1604629733:0;docker exec -it 03bfe90be2ea bash
: 1604645341:0;kubectl get po | grep faust
: 1604645360:0;kubectl logs -f faust-conversion-broadcast-7494fdbff5-26j2f
: 1604645470:0;[200~kubectl port-forward svc/consul-ui 8501:80~
: 1604645475:0;kubectl port-forward svc/consul-ui 8501:80~
: 1604646808:944;kubectl port-forward svc/consul-ui 8501:80
: 1604649548:1;kubectl get deployment
: 1604649559:0;kubectl delete deployment faust-events-campaign
: 1604649568:0;kubectl delete deployment faust-session-update
: 1604649584:0;kubectl delete faust-conversion-broadcast
: 1604649996:0;kubectl get po | grep faust
: 1604650016:0;kubectl get logs -f faust-profile-update-6ff867b7c8-zg4tf
: 1604650025:178;kubectl logs -f faust-profile-update-6ff867b7c8-zg4tf
: 1604650205:1;kubectl get po | grep faust
: 1604650230:0;kubectl delete deployment faust-conversion-broadcast-686db4b8bc-m78t4
: 1604650262:0;kubectl delete deployment faust-conversion-broadcast
: 1604650323:0;kubectl get po | grep faust
: 1604650531:3629;kubectl logs -f faust-profile-update-6ff867b7c8-zg4tf
: 1604654828:0;clear
: 1604654832:0;kubectl get po | grep faust
: 1604655120:1;kubectl get po 
: 1604655164:0;kubectl logs -f [200~event-processing-86777c896f-k48kr~
: 1604655180:3114;kubectl logs -f event-processing-86777c896f-k48kr
: 1604660280:0;clear
: 1604660643:0;kubectl get deployment
: 1604660652:4;kubectl delete deployment faust-session-update
: 1604660721:0;kubectl get po | grep faust
: 1604661189:0;kubectl get po  | grep fast
: 1604661192:0;kubectl get po  | grep eve
: 1604661214:0;kubectl logs -f event-processing-55b866c9d7-85pkc
: 1604652353:0;kubectl get po 
: 1604652363:0;kubectl logs -f [200~event-processing-5bdffcdd85-pk82v~
: 1604652370:2441;kubectl logs -f event-processing-5bdffcdd85-pk82v
: 1604654944:5;kubectl get po | grep faust
: 1604654954:0;kubectl get po
: 1604654997:1;kubectl get po | grep faust
: 1604655020:0;kubectl get po
: 1604657100:0;clear
: 1604657108:1;kubectl get po | grep faust
: 1604657123:0;kubectl logs -f 200~event-processing-5bdffcdd85-pk82v
: 1604657129:0;kubectl logs -f event-processing-5bdffcdd85-pk82v
: 1604657137:0;kubectl get po | grep faust
: 1604657169:57;kubectl logs -f faust-events-campaign-5d6f4f45c5-7bsj6
: 1604657230:0;kubectl get po | grep faust
: 1604657239:443;kubectl logs -f faust-events-campaign-5d6f4f45c5-7bsj6
: 1604658725:0;kubectl get po | grep faust
: 1604658730:0;kubectl get po
: 1604658739:1042;kubectl logs -f event-processing-67fb7db79c-fgkwq
: 1604660046:1;kubectl get po | grep faust
: 1604660276:0;clear
: 1604660340:0;kubectl get po | grep faust
: 1604660349:0;kubectl logs -f [200~faust-session-update-7fbc498ddb-j296q~
: 1604660357:336;kubectl logs -f faust-session-update-7fbc498ddb-j296q
: 1604666395:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1604736231:0;ls
: 1604736235:0;which python
: 1604736242:0;python3 --version
: 1604736246:0;python3 test.py
: 1604736694:0;ls
: 1604736700:0;which python3
: 1604891143:0;export
: 1604891157:0;export | grep CONFIG
: 1604920064:824;ssh root@103.57.210.44
: 1604923240:0;kubectl get po | faust
: 1604923243:1;kubectl get po | grep faust
: 1604926406:0;kubectl logs -f faust-session-update-7f979b9454-m5tl7
: 1604926415:0;kubectl get po | grep faust
: 1604886544:4;		docker-compose up -d
: 1604886549:0;A
: 1604886579:0;		docker-compose up -d
: 1604886560:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1604901549:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1604912069:0;git ss
: 1604914264:0;git s
: 1604914283:0;git cm "write test case for campaign service"
: 1604914285:0;git a .
: 1604914286:0;git cm "write test case for campaign service"
: 1604914287:0;git s
: 1604914291:4;git pull origin develop
: 1604914304:6;git push origin develop
: 1604926042:0;git s
: 1604926049:0;git a .
: 1604926065:0;git cm "changed path utm campaign"
: 1604926067:6;git push origin develop
: 1604974007:0;kubectl get po | grep faust
: 1604975981:7;kubectl logs -f faust-session-update-65df5c7ddb-rsdmj
: 1604975991:0;kubectl get po | grep faust
: 1604976018:269;kubectl logs -f faust-events-campaign-5d6f4f45c5-7bsj6
: 1604976289:0;kubectl get po | grep faust
: 1604978146:5;kubectl logs -f faust-conversion-broadcast-5fd9cbf4c5-sszgn
: 1604979184:0;kubectl get po 
: 1604979200:0;kubectl delete deployment faust-session-update
: 1604979266:0;kubectl get po 
: 1604980325:0;kubectl delete deployment faust-conversion-broadcast
: 1604991337:1;kubectl config show
: 1604991341:0;kubectl config view
: 1604991362:0;kubectl config view --flatten
: 1604991829:0;nslookup lb-apiserver.kubernetes.local
: 1604991845:0;cat /etc/hosts
: 1604993144:0;kubectl get po | grep faust
: 1604993156:301;kubectl logs -f faust-events-campaign-5d6f4f45c5-7bsj6
: 1604993461:0;kubectl get po | grep faust
: 1604993478:0;kubectl delete deployment faust-events-campaign
: 1605002291:0;kubectl get po | grep faus
: 1605005712:0;kubectl get po | grep faust
: 1605006094:0;kubectl logs -f faust-events-campaign-7bccf55c8f-mqgds
: 1605005775:0;kubectl get po | grep faust
: 1605006100:0;kubectl logs -f faust-session-update-79c664bc46-xgnqx
: 1604976365:1;		docker-compose up -d
: 1604978655:0;kubectl get po 
: 1604978680:0;kubectl logs -f faust-session-update-65df5c7ddb-rsdmj          1/1     Running     0          14h
: 1604978685:546;kubectl logs -f faust-session-update-65df5c7ddb-rsdmj  
: 1605000014:0;ls
: 1605000042:1;python3 app.py example
: 1605000104:0;python3 app.py
: 1605000392:1;python3 app.py worker --help
: 1605000529:0;python3 app.py worker --version
: 1605000535:0;python3 app.py worker --help
: 1605000543:1;python3 app.py
: 1605000549:2;python3 app.py agents
: 1605000565:0;cd ..
: 1605000570:0;ls
: 1605000604:1;python ./profile_update/app.py agent
: 1605000614:0;python ./profile_update/app.py agents
: 1605000621:0;cd ..
: 1605000638:0;ls
: 1605000641:0;cd workflows
: 1605000654:0;python3 ./conversion_broadcast/app.py agents
: 1605000666:0;cd ..
: 1605000667:0;ls
: 1605000670:0;cd workflows
: 1605000672:0;cd test_faust
: 1605000672:0;ls
: 1605000680:1;python3 app.py
: 1605000757:1;python3 app.py example
: 1605001706:0;git s
: 1605001710:0;git a .
: 1605001719:0;git cm "add test faust module"
: 1605001722:0;git checkout develop
: 1605001724:0;git
: 1605002523:1;git s
: 1605002639:0;git checkout -b metric_per_row
: 1605004171:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1604980340:11709;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1604992670:0;git a .
: 1604992690:0;git cm "changing conversion event to model topic"
: 1604992695:0;git checkout develop
: 1604995342:6531;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1604993487:3;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1604993494:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6067
: 1604998054:8;faust -A prile.workflows.test_faust.app worker -l info -p 6069
: 1605001882:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1604995345:6525;faust -A prile.workflows.events_campaign_engagement.app worker -l info -p 6066
: 1605009389:0;docker ps
: 1605069120:0;kubectl get po | grep faust
: 1605069132:356;kubectl logs -f faust-session-update-79c664bc46-xgnqx
: 1605069522:0;kubectl get po | grep faust
: 1605069548:1;kubectl delete deployment faust-session-update
: 1605069179:1;kubectl get po | grep faust
: 1605069187:297;kubectl logs -f faust-events-campaign-7bccf55c8f-mqgds
: 1605069513:0;kubectl delete deployment faust-events-campaign
: 1605070222:0;kubectl get po | grep faust
: 1605084707:1;kubectl get po | grep faust-conversion-broadcast-74785f9857-dzj4d
: 1605084721:1;kubectl delete deployment faust-conversion-broadcast
: 1605085729:0;kubectl get po | grep faust
: 1605058781:0;docker exec -it 03bfe90be2ea bash
: 1605069052:0;docker exec -it 03bfe90be2ea bash
: 1605084876:0;./kafka-run-class.sh kafka.tools.GetOffsetShell --broker-list "10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094" --topic conversion-events
: 1605084887:0;docker ps
: 1605084894:0;docker exec -it 03bfe90be2ea bash
: 1605108009:1;kubectl get po | grep faust
: 1605105340:0;docker ps
: 1605105347:0;docker exec -it 03bfe90be2ea bash
: 1605157356:0;kubectl get po | grep faust
: 1605147598:0;docker ps
: 1605147604:0;docker exec -it 03bfe90be2ea bash
: 1605145129:0;faust -A prile.workflows.session_updated.app worker -l info -p 6065
: 1605154095:0;kubectl get po 
: 1605154121:794;kubectl logs -f event-processing-7cfc9d67ff-hqxsk 
: 1605145109:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605162997:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605145152:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1605145143:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1605154274:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605147595:1;		docker-compose up -d
: 1605154584:0;git a .
: 1605154592:0;git cm "fix reach goal api"
: 1605154615:0;git s
: 1605154622:8;git push origin develop
: 1605156723:0;git s
: 1605157190:0;git a .
: 1605157203:0;git cm "add reach goal key"
: 1605157206:6;git push origin develop
: 1605162528:1;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605163674:1;kubectl get po | grep faust
: 1605169938:0;docker ps
: 1605169952:0;clear
: 1605169965:0;docker exec -it 03bfe90be2ea /bin/bash
: 1605168638:0;docker ps
: 1605168644:0;docker exec -it 03bfe90be2ea bash
: 1605163793:0;docker ps
: 1605163805:0;docker exec -it 03bfe90be2ea bash
: 1605167944:0;kubectl get deployment | grep profle
: 1605167947:0;kubectl get deployment | grep profile
: 1605167967:0;kubectl delete deployment faust-profile-update
: 1605203552:0;kubectl get po | grep faust
: 1605203561:1;kubectl logs -f faust-session-update-78455784b6-hjg6p
: 1605203720:0;kubectl get po | grep faust
: 1605203766:0;kubectl logs -f faust-session-update-78455784b6-hjg6p
: 1605203782:1;kubectl get po | grep faust
: 1605203793:6;kubectl logs -f faust-profile-update-77bb6b4cd6-488q8
: 1605203801:1;kubectl get po | grep faust
: 1605203811:0;kubectl logs -f faust-session-update-d76bcb88-rjgr5
: 1605258221:1175;kubectl port-forward svc/consul-ui 8501:80
: 1605261164:0;export
: 1605261182:0;export | grep CONFI
: 1605261189:0;export
: 1605264324:0;kubectl get pd
: 1605264327:0;kubectl get po
: 1605264364:51;kubectl edit deployment unomi
: 1605264440:0;kubectl get po | grep fast
: 1605264448:39;kubectl logs -f stag-fast-api-event-processing-54d8cb4ddf-2j94j
: 1605264534:0;kubectl get po | grep fast
: 1605264536:0;kubectl get po | grep faust
: 1605264709:0;kubectl get po | grep fast
: 1605264716:0;kubectl logs -f fast-api-event-processing-79654b848b-t428c
: 1605248771:0;docker ps
: 1605248779:0;docker exec -it 03bfe90be2ea bash
: 1605253119:1;docker ps
: 1605253124:0;docker exec -it 03bfe90be2ea bash
: 1605247153:1;kubectl get po | grep faust
: 1605247183:0;kubectl delete deployment faust-conversion-broadcast
: 1605247209:0;kubectl delete deployment faust-reach-goal
: 1605247265:0;kubectl delete deployment faust-session-update-667949579b-g9p2j
: 1605247269:0;kubectl delete deployment faust-session-update
: 1605248465:0;kubectl delete deployment faust-session-update-667949579b-g9p2j
: 1605248466:0;clear
: 1605248473:0;kubectl get deployment | grep faust
: 1605248483:0;kubectl delete deployment faust-conversion-broadcast-stag
: 1605248506:0;kubectl delete deployment faust-reach-goal-stag
: 1605248518:0;kubectl delete deployment faust-session-update-stag
: 1605254393:0;kubectl get deployment | grep faust
: 1605254394:0;clear
: 1605254418:1;kubectl get deployment | grep stag
: 1605254450:0;kubectl delete deployment faust-session-update-stag
: 1605254451:0;kubectl get deployment | grep stag
: 1605262257:97;kubectl port-forward svc/consul-ui 8501:80
: 1605262363:0;kubectl get po | grep fast
: 1605262405:0;kubectl get po | grep faust
: 1605262414:0;kubectl get po | grep event
: 1605264191:568;kubectl port-forward svc/consul-ui 8501:80
: 1605264937:0;clear
: 1605265329:11;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605265349:331;kubectl port-forward svc/consul-ui 8501:80
: 1605266620:0;kubectl get po | grep faust
: 1605266628:1045;kubectl logs -f faust-profile-update-78c6bcd488-9rt2z
: 1605267680:312;kubectl port-forward svc/consul-ui 8501:80
: 1605268046:0;kubectl get po | grep faust
: 1605262651:0;kubectl get po | grep event
: 1605262664:0;kubectl get po | grep fast
: 1605262672:0;kubectl get po | grep event
: 1605262683:0;kubectl logs -f event-processing-7c95cf99bc-kjlrj
: 1605262958:0;kubectl get po | grep event
: 1605262960:0;kubectl get po | grep faust
: 1605263162:0;kubectl get po | grep fast
: 1605263171:0;kubectl get po | grep event
: 1605263177:1;kubectl get deployment
: 1605264046:0;kubectl get po | grep fast
: 1605264048:0;kubectl get po | grep event
: 1605264065:0;kubectl delete deployment event-processing-599bcb9ddf-ffwk5
: 1605264069:0;kubectl delete deployment event-processing
: 1605264072:0;kubectl get po | grep event
: 1605264085:0;kubectl delete event-processing-demo-8678ff5f55-d75rm
: 1605264088:0;kubectl delete event-processing-demo
: 1605264094:0;kubectl delete deployment event-processing-demo
: 1605264100:0;kubectl get po | grep event
: 1605264106:0;kubectl get po | grep fast
: 1605264138:0;kubectl get po | grep event
: 1605264164:0;kubectl get po | grep fast
: 1605264172:16;kubectl logs -f fast-api-event-processing-79654b848b-xkv9p
: 1605264237:0;kubectl get po | grep fast
: 1605264277:0;kubectl delele pod fast-api-event-processing-79654b848b-xkv9p stag-fast-api-event-processing-54d8cb4ddf-56htl 
: 1605264287:59;kubectl delete pod fast-api-event-processing-79654b848b-xkv9p stag-fast-api-event-processing-54d8cb4ddf-56htl 
: 1605264958:0;kubectl get po | grep faust
: 1605265027:0;kubectl delete deployment faust-conversion-broadcast-stag
: 1605265040:0;kubectl delete deployment faust-profile-update
: 1605265080:0;kubectl delete deployment faust-segments-users-update-stag
: 1605265084:1;kubectl get po | grep faust
: 1605265098:0;kubectl delete deployment faust-segments-users-update-stag-68d898d6cf-qgdqw
: 1605265114:0;kubectl delete deployment faust-segments-users-update-stag
: 1605265116:0;kubectl get po | grep faust
: 1605265138:0;kubectl deployment faust-profile-update-stag-7f56847869-77t9z
: 1605265144:0;kubectl deployment faust-profile-update-stag
: 1605265152:0;kubectl deployment deployment faust-profile-update-stag
: 1605265155:0;kubectl get po | grep faust
: 1605265171:0;kubectl delete deployment faust-profile-update-stag
: 1605265174:0;kubectl get po | grep faust
: 1605265195:0;kubectl delete deployment faust-profile-update-stag
: 1605265202:0;kubectl get po | grep faust
: 1605265215:0;kubectl delete deployment faust-profile-update-stag
: 1605265237:1;kubectl get po | frep faust
: 1605265242:0;kubectl get po | grep faust
: 1605265271:1;kubectl delete deployment faust-reach-goal-stag
: 1605265274:0;kubectl get po | grep faust
: 1605265604:0;clear
: 1605265609:1;kubectl get po | grep fast
: 1605265621:311;kubectl logs -f fast-api-event-processing-79654b848b-t428c
: 1605265940:0;kubectl get po | grep faust
: 1605265953:5;kubectl logs -f faust-segments-users-update-5cb99969f4-zpbpb
: 1605318291:0;export | grep CONFIG
: 1605318299:0;		docker-compose up -d
: 1605318311:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605318404:0;kubectl get po | grep fast
: 1605318522:0;kubectl port-forward svc/consul-ui 8501:80
: 1605318613:0;docker ps
: 1605318624:0;		docker-compose up -d
: 1605318627:0;docker ps
: 1605318634:0;docker exec -it 03bfe90be2ea bash
: 1605318800:0;kubectl get po | grep faust
: 1605318809:0;kubectl logs -f faust-profile-update-78c6bcd488-9rt2z
: 1605319023:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1605319036:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1605319185:0;faust -A prile.workflows.session_updated.app worker -l info -p 6065
: 1605319669:0;git s
: 1605319695:0;kubectl get po | grep fast
: 1605319706:0;kubectl logs -f fast-api-event-processing-79d5dfc464-drhpv
: 1605319776:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605321278:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605321404:0;export | grep CONFIG
: 1605322292:0;kubectl get po | grep faust
: 1605323733:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605324508:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605324536:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1605324905:0;export | grep CONFI
: 1605324922:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1605324988:0;kubectl port-forward svc/consul-ui 8501:80
: 1605325065:0;kubectl get po | grep fast
: 1605325078:0;git s
: 1605325083:0;git a .
: 1605325096:0;git cm "config redis database"
: 1605325109:0;git push origin master
: 1605325120:0;git checkout develop
: 1605325123:0;git merge master
: 1605325133:0;git pull origin develop
: 1605325139:0;git tree
: 1605325156:0;git push origin develop
: 1605325169:0;git checkout staging
: 1605325174:0;git merge develop
: 1605325187:0;git s
: 1605325191:0;git push origin sta
: 1605325195:0;git push origin staging
: 1605325210:0;git pull origin staging
: 1605325388:0;git s
: 1605325414:0;git cm "[staging] merged with brian api campaign"
: 1605325415:0;git s
: 1605325419:0;git tree
: 1605325430:0;git s
: 1605325438:0;git push origin staging
: 1605325446:0;git s
: 1605325452:0;git tree
: 1605325488:0;git s
: 1605325491:0;git tree
: 1605325956:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605326094:0;kubectl port-forward svc/consul-ui 8501:80
: 1605326129:0;kubectl get po | grep faust
: 1605328045:0;clear
: 1605328054:0;kubectl get po | grep fast
: 1605328067:0;kubectl get po | grep faust
: 1605328108:0;kubectl logs -f stag-faust-conversion-broadcast-76d4597c8d-g5h4l
: 1605328154:0;kubectl port-forward svc/consul-ui 8501:80
: 1605328281:0;kubectl get po | grep faust
: 1605328292:0;kubectl logs -f stag-faust-profile-update-58864c8565-wdr2l
: 1605328477:0;kubectl logs -f stag-faust-profile-update-58864c8565-wdr2l | grep 10.110
: 1605328603:0;kubectl get po | grep faust
: 1605328628:0;kubectl get po | grep stag-faust-profile
: 1605328637:0;kubectl logs -f stag-faust-profile-update-5bc9d6564f-cqllx
: 1605328677:0;kubectl port-forward svc/consul-ui 8501:80
: 1605329399:0;clear
: 1605329448:0;kubectl get po | grep faust
: 1605329462:0;kubectl logs -f stag-faust-profile-update-dc68fc779-gs8c8
: 1605329596:0;kubectl get po | grep faust
: 1605329606:0;kubectl delete stag-faust-profile-update-dc68fc779-gs8c8
: 1605329611:0;kubectl delete po stag-faust-profile-update-dc68fc779-gs8c8
: 1605329619:0;kubectl get po | grep faust
: 1605329643:0;kubectl logs -f stag-faust-profile-update-dc68fc779-mzr2t
: 1605329929:0;clear
: 1605329935:0;kubectl get po | grep faust
: 1605329944:0;kubectl logs -f stag-faust-profile-update-77cdf9d748-dkl6b
: 1605329994:0;faust -A prile.workflows.session_updated.app worker -l info -p 6065
: 1605330001:0;faust -A prile.workflows.session_updated.app worker -l info -p 6066
: 1605330051:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6069
: 1605330352:0;kubectl logs -f stag-faust-profile-update-77cdf9d748-dkl6b
: 1605335678:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605336919:0;export | grep CONF
: 1605336943:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605338371:0;clear
: 1605338378:0;kubectl get po | grep faust
: 1605338388:0;kubectl logs -f faust-profile-update-6fd754465b-4xc9k
: 1605339076:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605339366:0;git s
: 1605339496:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605339568:0;git s
: 1605339880:0;git a .
: 1605339928:0;git cm "set validation for profile update processor"
: 1605339934:0;git s
: 1605339953:0;git checkout develop
: 1605339960:0;git merge staging
: 1605339966:0;git tree
: 1605339982:0;git checkout staging
: 1605339988:0;git push origin staging
: 1605340512:0;docker run -it -p 80:80 xeotek/kadeck-allinone:latest
: 1605341081:0;docker run -it -p 8081:80 xeotek/kadeck-allinone:latest
: 1605341269:0;docker images
: 1605341300:0;docker rm xeotek/kadeck-allinone
: 1605341309:0;docker --help
: 1605341318:0;docker rmi xeotek/kadeck-allinone
: 1605341344:0;docker container | grep dake
: 1605341349:0;docker container ps | grep dake
: 1605341354:0;docker container ps -a | grep dake
: 1605341358:0;docker container ps -a
: 1605341386:0;clear
: 1605341388:0;docker ps
: 1605341893:0;docker pull digitsy/kafka-magic
: 1605341940:0;docker run -d --rm -p 8081:80  digitsy/kafka-magic
: 1605342682:0;		docker-compose up -d
: 1605342699:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605342766:0;		docker-compose up -d
: 1605342784:0;docker ps
: 1605342905:0;ping localhost:9092
: 1605342916:0;telnet localhost
: 1605342936:0;telnet 0.0.0.0 9092
: 1605343196:0;docker ps
: 1605343797:0;docker exec -it 03bfe90be2ea bash
: 1605344062:0;docker stop $(docker ps -aq)
: 1605344090:0;		docker-compose up -d
: 1605344095:0;ls
: 1605344106:0;		docker-compose up -d
: 1605344371:0;export kafka
: 1605344379:0;docker ps
: 1605344449:0;docker run -d --rm -p 8080:80 digitsy/kafka-magic
: 1605344661:0;docker run -d --rm -p 8082:80 digitsy/kafka-magic
: 1605344669:0;docker run -d --rm -p 8079:80 digitsy/kafka-magic
: 1605344712:0;docker stop $(docker ps -aq)
: 1605344734:0;		docker-compose up -d
: 1605344770:0;docker ps
: 1605344778:0;		docker-compose up -d
: 1605344793:0;docker ps
: 1605344821:0;git s
: 1605344856:0;docker exec -it 4d71b8a3251e 
: 1605344865:0;docker exec --help
: 1605344916:0;docker exec -it 4d71b8a3251e /bash
: 1605344941:0;docker exec -it 4d71b8a3251e bash
: 1605345162:0;kubectl get po | grep faust
: 1605346758:0;kubectl logs -f stag-faust-session-update-f46798c99-zlrfx
: 1605346780:0;kubectl logs -f stag-faust-reach-goal-775797f9f7-ppkgc
: 1605346893:0;docker ps
: 1605346902:0;docker exec -it 4d71b8a3251e bash
: 1605347605:0;kubectl get po | grep faust
: 1605347614:0;kubectl logs -f stag-faust-segments-users-update-85d966fdd7-bg9vk
: 1605347766:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605348277:0;sudo snap install gitkraken --classic
: 1605491833:0;git checkout develop
: 1605491838:0;git s
: 1605491874:0;git a .
: 1605492121:0;git cm "remove import unnecessary\
"
: 1605492123:0;git s
: 1605492252:0;git tree
: 1605492265:0;git merge staging
: 1605492268:0;git s
: 1605492271:0;git tree
: 1605492288:0;git push origin develop
: 1605492297:0;git tree
: 1605492343:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605492800:0;kubectl get po | grep faust
: 1605492821:0;kubectl logs -f faust-profile-update-6fd754465b-4xc9k
: 1605492833:0;kubectl get po | grep faust
: 1605492852:0;kubectl logs -f faust-segments-users-update-6f99447786-tzt5r
: 1605492856:0;kubectl get po | grep faust
: 1605498773:0;kubectl logs -f faust-profile-update-6fd754465b-4xc9k 
: 1605498785:0;kubectl logs -f faust-profile-update-6fd754465b-4xc9k | grep DD9BkT1FRPgar6kXMxkQv9CIDzW
: 1605498893:0;kubectl logs -f faust-profile-update-6fd754465b-4xc9k
: 1605498911:0;		docker-compose up -d
: 1605498925:0;docker ps
: 1605498937:0;		docker-compose up -d
: 1605498940:0;docker ps
: 1605498945:0;docker exec -it 4d71b8a3251e bash
: 1605499106:0;git tree
: 1605499154:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605499383:0;kubectl get po | grep faust
: 1605499393:0;kubectl logs -f faust-profile-update-dd9ffb86d-r2jpz
: 1605499453:0;kubectl get po | grep faust
: 1605499482:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605499571:0;docker ps
: 1605499577:0;docker exec -it 4d71b8a3251e bash
: 1605499671:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605500431:0;kubectl port-forward svc/consul-ui 8501:80
: 1605500493:0;export | grep CONFI
: 1605500506:0;export CONFIG_NAMESPACE=eventify/prod
: 1605500510:0;export | grep CONFI
: 1605500518:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605500652:0;git s
: 1605500716:0;git cm "fix conversion"
: 1605500717:0;git s
: 1605500720:0;git a.
: 1605500722:0;git a .
: 1605500726:0;git cm "fix conversion"
: 1605500736:0;git checkout staging
: 1605500739:0;git merge develop
: 1605500745:0;git checkout develop
: 1605500925:0;kubectl get po | grep faust
: 1605501060:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605501266:0;kubectl logs -f faust-profile-update-dd9ffb86d-r2jpz
: 1605503423:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605505306:0;kubectl logs -f faust-profile-update-dd9ffb86d-r2jpz
: 1605505310:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605505333:0;kubectl logs -f faust-profile-update-dd9ffb86d-r2jpz
: 1605505336:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605505405:0;kubectl logs -f faust-profile-update-dd9ffb86d-r2jpz
: 1605505417:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605505489:0;clear
: 1605507007:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605507010:0;clear
: 1605507011:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605507908:0;clear
: 1605508162:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605510396:0;kubectl get po | grep faust
: 1605510512:0;docker ps
: 1605510518:0;docker exec -it 4d71b8a3251e bash
: 1605510872:0;sudo apt install ./Conduktor-2.0.13.deb
: 1605510972:0;ls
: 1605513504:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605513547:0;kubectl get po | grep faust
: 1605513561:0;kubectl logs -f faust-profile-update-dd9ffb86d-r2jpz
: 1605513580:0;kubectl delete po faust-profile-update-dd9ffb86d-r2jpz
: 1605513786:0;kubectl logs -f faust-profile-update-dd9ffb86d-r2jpz
: 1605513792:0;kubectl get po | grep faust
: 1605513806:0;kubectl logs -f faust-profile-update-dd9ffb86d-jlzb7
: 1605513856:0;kubectl get po | grep faust
: 1605513863:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605513897:0;kubectl get po | grep faust
: 1605513919:0;kubectl exec -it faust-conversion-broadcast-78b9996659-gx46m bash
: 1605514188:0;clear
: 1605514200:0;kubectl get po | grep faust
: 1605514286:0;kubectl logs -f faust-profile-update-dd9ffb86d-jlzb7
: 1605514292:0;kubectl get po | grep faust
: 1605514307:0;kubectl logs -f faust-conversion-broadcast-78b9996659-gx46m
: 1605514317:0;kubectl delete po faust-conversion-broadcast-78b9996659-gx46m
: 1605514608:0;clear
: 1605514646:0;kubectl get po | grep faust
: 1605514672:0;kubectl logs -f faust-profile-update-dd9ffb86d-jlzb7
: 1605514700:0;kubectl logs -f faust-conversion-broadcast-78b9996659-mghqf
: 1605514776:0;kubectl logs -f stag-faust-segments-users-update-656fb5bdb8-gg8lp
: 1605514802:0;kubectl delete po faust-segments-users-update-6f99447786-tzt5r
: 1605514840:0;kubectl detele po faust-reach-goal-667c599bd4-r9wbh
: 1605514854:0;kubectl delete po faust-reach-goal-667c599bd4-r9wbh
: 1605514866:0;kubectl logs -f faust-segments-users-update-6f99447786-tzt5r
: 1605514872:0;kubectl get po | grep faust
: 1605514884:0;kubectl logs -f faust-segments-users-update-6f99447786-hx8kn
: 1605514922:0;kubectl delete po faust-session-update-86d7999cb8-2ldmr
: 1605514928:0;kubectl get po | grep faust
: 1605514951:0;kubectl logs -f faust-reach-goal-667c599bd4-pxjvh
: 1605514969:0;kubectl get po | grep faust
: 1605515006:0;kubectl logs -f faust-session-update-86d7999cb8-mxhgr
: 1605515230:0;kubectl get po | grep faust
: 1605515354:0;clear
: 1605515356:0;kubectl get po | grep faust
: 1605515390:0;kubectl logs -f faust-events-campaign-657654f95b-f9mvv
: 1605517098:0;kubectl get po | grep faust
: 1605517109:0;kubectl logs -f faust-session-update-86d7999cb8-mxhgr
: 1605522187:0;git s
: 1605522222:0;git checkout -b profile_automic_schema
: 1605522224:0;git s
: 1605522225:0;clear
: 1605522239:0;export | grep CONFIG
: 1605534744:0;		docker-compose up -d
: 1605534763:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605543533:0;		docker-compose up -d
: 1605543537:0;1
: 1605543539:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605577739:0;		docker-compose up -d
: 1605577744:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605582046:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605587447:0;export | grep CONFIG
: 1605587648:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605588190:0;git s
: 1605588197:0;git a .
: 1605588215:0;git cm "move schema profile"
: 1605588220:0;git checkout develop
: 1605588231:0;git pull origin develop
: 1605588317:0;git s
: 1605588324:0;git cm "remove hard code tenant"
: 1605588327:0;git a .
: 1605588339:0;git cm "remove hard code tenant"
: 1605588352:0;git checkout staging
: 1605588361:0;git merge develop
: 1605588682:0;git checkout profile_automic_schema
: 1605588685:0;git s
: 1605588715:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605589410:0;git checkout develop
: 1605589418:0;git tree
: 1605589447:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605591404:0;git s
: 1605591414:0;git checkout staging
: 1605591419:0;git push origin staging
: 1605592963:0;git s
: 1605592972:0;git checkout staging
: 1605592980:0;git checkout 
: 1605592986:0;git checkout profile_automic_schema
: 1605592987:0;git s
: 1605593023:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605593981:0;clear
: 1605593997:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605594306:0;kubectl get po | grep faust
: 1605594321:0;kubectl delete po faust-conversion-broadcast-78b9996659-mghqf
: 1605594359:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605594374:0;kubectl get po | grep faust
: 1605594393:0;clear
: 1605594395:0;kubectl get po | grep faust
: 1605594414:0;kubectl delete deployment faust-conversion-broadcast
: 1605594416:0;kubectl get po | grep faust
: 1605594439:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605596629:0;which faust
: 1605596683:0;cat {
: 1605596689:0;which faust
: 1605596699:0;cat /home/chile/PycharmProjects/Github/PrimeData/event-processing/.prile/bin/faust
: 1605597016:0;clear
: 1605597021:0;env | grep config
: 1605597026:0;env | grep CONFIG
: 1605598358:0;clear
: 1605598366:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605600856:0;faust -A prile.workflows.profile_update.app worker -l info -p 6068
: 1605602515:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605602520:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1605606260:0;export | grep CONF
: 1605606638:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1605613417:0;git s
: 1605613420:0;git a .
: 1605613467:0;git cm "changed profile update and conversion broadcast to profile schema automic"
: 1605613469:0;git s
: 1605622687:0;git push origin master
: 1605622711:0;git
: 1605622712:0;git s
: 1605622723:0;clear
: 1605622849:0;		docker-compose up -d
: 1605622899:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605664543:0;gits
: 1605664546:0;git s 
: 1605664568:0;		docker-compose up -d
: 1605664585:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605665285:0;kubectl get po | grep faust
: 1605665292:0;kubectl port-forward svc/consul-ui 8501:80
: 1605665773:0;kubectl get po | grep faust
: 1605665907:0;kubectl logs -f stag-faust-segments-users-update-856556c9c6-j968j
: 1605665926:0;kubectl get po | grep faust
: 1605665940:0;kubectl logs -f stag-faust-segments-users-update-856556c9c6-j968j
: 1605666047:0;kubectl logs -f stag-faust-profile-update-b88858ff4-txpvw
: 1605666950:0;kubectl port-forward svc/consul-ui 8501:80
: 1605666981:0;kubectl logs -f stag-faust-profile-update-b88858ff4-txpvw
: 1605668524:0;git s
: 1605669699:0;git checkout develop
: 1605669702:0;git a .
: 1605669709:0;git cm "edit sql"
: 1605669712:0;git checkout develop
: 1605669717:0;git pull origin develop
: 1605670274:0;git 
: 1605670277:0;git s
: 1605670284:0;git a .
: 1605670301:0;git cm "add info adjacency_list"
: 1605670302:0;git s
: 1605670321:0;git checkout profile_automic_schema
: 1605670322:0;git
: 1605670323:0;git s
: 1605673822:0;kubectl port-forward svc/consul-ui 8501:80
: 1605673825:0;git s
: 1605673835:0;kubectl get po | grep faust
: 1605673851:0;kubectl delete deployment stag-faust-profile-update-b88858ff4-txpvw
: 1605673858:0;kubectl delete deployment stag-faust-profile-update
: 1605673861:0;kubectl get po | grep faust
: 1605673890:0;kubectl delete deployment stag-faust-conversion-broadcast
: 1605673907:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605673991:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605674204:0;git s
: 1605674219:0;git a .
: 1605674250:0;git cm "extracting data for graph event topic"
: 1605674252:0;git checkout develop
: 1605674313:0;git checkout profile_automic_schema
: 1605675033:0;export | grep CONFI
: 1605680052:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605680459:0;export | grep CONFI
: 1605680466:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605681536:0;git s
: 1605682168:0;clear
: 1605689566:0;git s
: 1605689569:0;git a .
: 1605689616:0;git cm "edited sql to new profile automic"
: 1605689618:0;git s
: 1605701287:0;git push origin profile_automic_schema
: 1605707227:0;		docker-compose up -d
: 1605707238:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605711682:0;kubectl get po | grep faust
: 1605711695:0;kubectl delete deployment stag-faust-segments-users-update
: 1605715532:0;kubectl get po | grep faust
: 1605715740:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605719906:0;git a .
: 1605719957:0;git cm "changed segment user update to automic schema"
: 1605719960:0;git s
: 1605719967:0;git push origin profile_automic_schema
: 1605751406:0;		docker-compose up -d
: 1605751420:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605751518:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605752087:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605752783:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605754404:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605758655:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605767093:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605767212:0;kubectl port-forward svc/consul-ui 8501:80
: 1605771862:0;clear
: 1605771863:0;git s
: 1605771873:0;kubectl get po | grep faust
: 1605771923:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605772067:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605773505:0;git s
: 1605773507:0;git a .
: 1605773555:0;git cm "changed segment sql to automic schema"
: 1605773556:0;git s
: 1605773562:0;git push origin profile_automic_schema
: 1605773623:0;git merge staging
: 1605773784:0;git fetch
: 1605773798:0;git merge origin staging
: 1605773851:0;git s
: 1605773872:0;git tree
: 1605773887:0;git stash save 'merge with stag'
: 1605773891:0;git s
: 1605773904:0;git stash
: 1605773948:0;git s
: 1605773979:0;git status
: 1605774006:0;git commit 
: 1605774019:0;git status
: 1605774084:0;git merge origin/staging
: 1605774165:0;git tree
: 1605774175:0;git 
: 1605774176:0;git s
: 1605775279:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605775563:0;kubectl port-forward svc/consul-ui 8501:80
: 1605775659:0;kubectl get po | grep fast
: 1605775665:0;kubectl logs -f stag-fast-api-event-processing-6b89c6d846-fdtb2
: 1605775693:0;git s
: 1605775694:0;git tree
: 1605775720:0;git checkout staging
: 1605775724:0;git merge profile_automic_schema
: 1605775728:0;git tree
: 1605775738:0;git a .
: 1605775756:0;git cm "remove hard code in sql"
: 1605775757:0;git s
: 1605775769:0;git checkout staging
: 1605775773:0;git merge profile_automic_schema
: 1605775774:0;git s
: 1605775780:0;git push origin staging
: 1605775915:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605776335:0;git pull origin staging
: 1605776361:0;git s
: 1605776603:0;git merge origin/campaign_performance_ts
: 1605776605:0;git s
: 1605776925:0;git tree
: 1605776938:0;git pull origin stagin
: 1605776942:0;git pull origin staging
: 1605776952:0;git a .
: 1605776956:0;git s
: 1605776969:0;git a .
: 1605776976:0;git cm "remove harcode in sql"
: 1605776981:0;git push origin staging
: 1605776988:0;git s
: 1605777075:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605777325:0;git status
: 1605777343:0;git fetch 
: 1605777355:0;git checkout staging
: 1605777362:0;git pull origin 
: 1605777376:0;git pull origin  staging
: 1605777763:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605777904:0;git s
: 1605777907:0;git a .
: 1605777925:0;git cm "remove code error after merge"
: 1605777926:0;git s
: 1605777930:0;git push origin staging
: 1605778000:0;git checkout develop
: 1605778014:0;git pull origin develop
: 1605778028:0;git merge staging
: 1605778032:0;git s
: 1605778046:0;git cm "[DEVELOP] merged with staging"
: 1605778048:0;git s
: 1605778281:0;git a .
: 1605778359:0;git cm "[DEVELOP] merged with staging"
: 1605778360:0;git s
: 1605778447:0;git push origin develop
: 1605778455:0;git s
: 1605778463:0;git checkout staging
: 1605778467:0;git merge develop
: 1605778713:0;git s
: 1605778780:0;git push origin staging
: 1605779035:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605779406:0;git a .
: 1605779417:0;git cm "fixed get num pros query"
: 1605779422:0;git push origin staging
: 1605780144:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605781627:0;git a .
: 1605781645:0;git cm "fixed get lastest profile filter pros key"
: 1605781649:0;git push origin staging
: 1605781709:0;export | grep CONF
: 1605781868:0;kubectl port-forward svc/consul-ui 8501:80
: 1605781917:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605782264:0;docker stop $(docker ps -aq)
: 1605782285:0;kubectl get nodes
: 1605782299:0;kubectl port-forward svc/consul-server 8500
: 1605782386:0;		docker-compose up -d
: 1605782401:0;git s
: 1605782404:0;git a .
: 1605782410:0;git cm "remove default consul"
: 1605782411:0;git s
: 1605782418:0;git tree
: 1605782471:0;docker stop $(docker ps -aq)
: 1605782490:0;kubectl port-forward svc/consul-ui 8500
: 1605782495:0;kubectl port-forward svc/consul-ui 80
: 1605782501:0;kubectl port-forward svc/consul-ui 80:8500
: 1605782507:0;kubectl port-forward svc/consul-ui 8500:80
: 1605782646:0;		docker-compose up -d
: 1605782670:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605786346:0;git pull  origin develop
: 1605793820:0;ls
: 1605793833:0;cat .zshrc
: 1605793846:0;nano .zshrc
: 1605835366:0;		docker-compose up -d
: 1605835534:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605835620:0;git s
: 1605835947:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605835962:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605835977:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1605835995:0;kubectl get po | grep faust
: 1605841727:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1605843401:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1605843575:0;git s
: 1605843849:0;git a .
: 1605845855:0;git s
: 1605845862:0;git a .
: 1605845923:0;git cm "update sql automic schema (segment user, segment size, profiles)"
: 1605845924:0;git s
: 1605845959:0;git push origin staging
: 1605846123:0;kubectl get po | grep faust
: 1605846291:0;git s
: 1605846576:0;git checkout master
: 1605846581:0;git merge staging
: 1605846583:0;git s
: 1605846588:0;git tree
: 1605847189:0;kubectl port-forward svc/consul-ui 8500:80
: 1605847210:0;kubectl port-forward svc/consul-ui 8501:80
: 1605847462:0;kubectl get po | grep faust
: 1605847605:0;kubectl logs -f stag-faust-segments-users-update-56ccbb4fbd-sqjvd
: 1605848354:0;git s
: 1605848361:0;git checkout staging
: 1605848362:0;git s
: 1605848371:0;export | grep CONFI
: 1605848427:0;export CONFIG_NAMESPACE=eventify/prod
: 1605848437:0;export | grep CONFI
: 1605848445:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605848454:0;export CONFIG_NAMESPACE=eventify/prod
: 1605848459:0;export | grep CONFI
: 1605848463:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605848507:0;kubectl port-forward svc/consul-ui 8501:80
: 1605848555:0;kubectl get po | grep fast
: 1605848562:0;kubectl logs -f fast-api-event-processing-678fdfb68b-6dbgz
: 1605848681:0;git checkout master
: 1605848684:0;git s
: 1605848686:0;git tree
: 1605848691:0;git push origin master
: 1605848701:0;git s
: 1605853061:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605853131:0;git s
: 1605853133:0;git a .
: 1605853152:0;git cm "fixed sql get histogram"
: 1605853175:0;git checkout staging
: 1605853179:0;git merge master
: 1605853190:0;git pull origin staging
: 1605853200:0;git push origin staging
: 1605853210:0;git checkout master
: 1605853213:0;git merge staging
: 1605853218:0;git push origin master
: 1605853362:0;git checkout staging
: 1605853480:0;git checkout master
: 1605853487:0;git checkout staging
: 1605854643:0;git checkout -b test
: 1605854679:0;git s
: 1605854829:0;git a .
: 1605854976:0;git s
: 1605854982:0;git cm "test git"
: 1605855125:0;git checkout -b test_1
: 1605855263:0;git s
: 1605855282:0;]
: 1605855711:0;cler
: 1605855712:0;clear
: 1605858570:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605860777:0;git checkout master
: 1605862146:0;clear
: 1605862153:0;kubectl logs -f fast-api-event-processing-678fdfb68b-6dbgz
: 1605862159:0;kubectl get po | grep faust
: 1605862286:0;kubectl get logs -f faust-segments-users-update-7c59d8c9d6-8wbhl
: 1605862291:0;kubectl logs -f faust-segments-users-update-7c59d8c9d6-8wbhl
: 1605862545:0;clear
: 1605862595:0;kubectl logs -f faust-segments-users-update-7c59d8c9d6-8wbhl
: 1605862620:0;kubectl get po | grep faust
: 1605862673:0;kubectl logs -f faust-segments-users-update-cc8948c58-zmzxj
: 1605862998:0;kubectl get po | grep faust
: 1605863011:0;kubectl logs -f faust-profile-update-7c869dc496-ss69f
: 1605863268:0;kubectl get po | grep faust
: 1605863283:0;kubectl logs -f faust-profile-update-7c869dc496-ss69f
: 1605863291:0;kubectl get po | grep faust
: 1605863343:0;kubectl logs -f faust-conversion-broadcast-7c955b95b7-r4s67
: 1605863694:0;kubectl get po | grep faust
: 1605863763:0;kubectl logs -f stag-faust-segments-users-update-56ccbb4fbd-sqjvd
: 1605863813:0;kubectl logs -f faust-conversion-broadcast-7c955b95b7-r4s67
: 1605864389:0;clear
: 1605864398:0;kubectl get po | grep faust
: 1605864402:0;clear
: 1605864428:0;kubectl logs -f faust-profile-update-746bb5868d-xkg2z
: 1605864438:0;clear
: 1605864441:0;kubectl logs -f faust-conversion-broadcast-7c955b95b7-r4s67
: 1605864456:0;kubectl logs -f faust-segments-users-update-cc8948c58-zmzxj
: 1605866170:0;export | grep CONFI
: 1605866183:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605867599:0;git s
: 1605867601:0;git a .
: 1605867631:0;git s
: 1605867653:0;git stash save 'fix get user sample not match str and num'
: 1605867663:0;git checkout staging
: 1605867676:0;git stash pop
: 1605867678:0;git s
: 1605867721:0;git push origin staging
: 1605867760:0;git checkout master
: 1605867765:0;git merge staging
: 1605867769:0;git push origin master
: 1605870838:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605870938:0;clear
: 1605870939:0;git s
: 1605870941:0;clear
: 1605871230:0;git a .
: 1605871264:0;git s
: 1605871291:0;git checkout staging
: 1605871292:0;git s
: 1605871294:0;git a 
: 1605871296:0;git a .
: 1605871339:0;git cm "fixed get num pros query"
: 1605871340:0;git s
: 1605871353:0;git push origin staging
: 1605871368:0;git pull origin staging
: 1605871418:0;git s
: 1605871423:0;git push origin staging
: 1605871460:0;git checkout master
: 1605871463:0;git merge staging
: 1605871472:0;git push origin master
: 1605923391:0;		docker-compose up -d
: 1605923399:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1605923413:0;kubectl get po | grep faust
: 1605923608:0;git s
: 1605925328:0;ls
: 1605925481:0;which pip3
: 1605925488:0;which python3
: 1605925498:0;python3
: 1605925548:0;clear
: 1605925553:0;which python3
: 1605925643:0;which python
: 1605925647:0;which python3
: 1605925711:0;pip3 install squarify
: 1605925734:0;pip3 install matplotlib
: 1605925822:0;ls
: 1605925823:0;pwd
: 1605925827:0;which python3
: 1605925833:0;which pop
: 1605925835:0;which pip
: 1605926310:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605927828:0;export | grep CONFI
: 1605927842:0;export CONFIG_NAMESPACE=eventify/prod
: 1605927847:0;export | grep CONFI
: 1605927851:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605928526:0;git a .
: 1605928543:0;git cm "added segment total user api"
: 1605928552:0;git push origin master
: 1605928840:0;git checkout stagin
: 1605928842:0;git checkout staging
: 1605928846:0;git merge master
: 1605928847:0;git s
: 1605929685:0;which python
: 1605929686:0;which python3
: 1605929691:0;jupyter
: 1605929696:0;jupyter notebook
: 1605930141:0;pip3 install jupyter-tabnine
: 1605930143:0;jupyter nbextension install --py jupyter_tabnine
: 1605930143:0;jupyter nbextension enable --py jupyter_tabnine
: 1605930151:0;jupyter serverextension enable --py jupyter_tabnine
: 1605930168:0;conda install -c conda-forge jupyter_nbextensions_configurator
: 1605930256:0;which pip3
: 1605930261:0;which python3
: 1605930268:0;jupyter notebook
: 1605930484:0;jupyter nbextension enable hinterland/hinterland
: 1605930571:0;which jupyter notebook
: 1605930580:0;which jupyter
: 1605930953:0;clear
: 1605930962:0;kubectl get po | grep faus
: 1605930975:0;kubectl logs -f faust-segments-users-update-cc8948c58-zmzxj
: 1605930981:0;kubectl get po | grep faus
: 1605931003:0;kubectl delete po faust-conversion-broadcast-7c955b95b7-r4s67
: 1605931083:0;kubectl get po | grep faus
: 1605931093:0;kubectl logs -f faust-conversion-broadcast-7c955b95b7-k7676
: 1605931099:0;kubectl get po | grep faus
: 1605931119:0;kubectl delete po faust-events-campaign-84649d8464-5pqhr faust-profile-update-746bb5868d-xkg2z
: 1605931192:0;kubectl delete faust-reach-goal-68d4bfd8d8-468km faust-segments-users-update-cc8948c58-zmzxj faust-session-update-67df5d6748-6fk5r
: 1605931198:0;kubectl get po | grep faus
: 1605931218:0;kubectl delete faust-session-update-67df5d6748-6fk5r faust-reach-goal-68d4bfd8d8-468km faust-session-update-67df5d6748-6fk5r
: 1605931249:0;kubectl delete po faust-reach-goal-68d4bfd8d8-468km faust-segments-users-update-cc8948c58-zmzxj faust-session-update-67df5d6748-6fk5r
: 1605931292:0;kubectl get po | grep faus
: 1605931305:0;kubectl logs -f faust-profile-update-746bb5868d-c2ptl
: 1605931444:0;kubectl get po | grep faus
: 1605931454:0;kubectl logs -f faust-profile-update-746bb5868d-c2ptl
: 1605931529:0;kubectl get po | grep faus
: 1605931538:0;kubectl logs -f stag-faust-conversion-broadcast-5474994d89-mpjwx
: 1605932089:0;kubectl get po | grep faus
: 1605932132:0;kubectl get po -aq
: 1605932136:0;kubectl get po --help
: 1605932180:0;kubectl get po | grep faus
: 1605932287:0;kubectl delete po stag-faust-adjacency-list-6fb6c9f874-4ptqc stag-faust-conversion-broadcast-5474994d89-mpjwx stag-faust-events-campaign-77cc68bfc6-h9x8g stag-faust-profile-update-75d6d485db-s7tlw  stag-faust-reach-goal-555f94899d-b8cdh  stag-faust-segments-users-update-56ccbb4fbd-sqjvd  stag-faust-session-update-598bcffd64-cjqhk
: 1605932545:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605932680:0;clear
: 1605932979:0;which python
: 1605933010:0;which python3
: 1605933016:0;which pip3
: 1605933446:0;clear
: 1605933450:0;which python3
: 1605933498:0;ls
: 1605933501:0;which python3
: 1605933514:0;pip3 install .
: 1605933527:0;which python3
: 1605933583:0;which python3.7
: 1605933604:0;clear
: 1605933660:0;python3
: 1605933666:0;which python3
: 1605933675:0;which pip3
: 1605933795:0;pip3
: 1605933799:0;which pip3
: 1605933993:0;which python
: 1605939446:0;clea
: 1605939448:0;clear
: 1605939493:0;pwd
: 1605939508:0;where python3
: 1605939518:0;which python3
: 1605939529:0;pip3 install -r
: 1605939532:0;pip3 install .
: 1605939656:0;clear
: 1605939657:0;pwd
: 1605939680:0;jupyternotebook
: 1605939684:0;jupyter notebook
: 1605939745:0;which conda
: 1605939752:0;conda
: 1605939775:0;conda install -c conda-forge jupyterlab
: 1605939797:0;jupyternotebooko
: 1605939804:0;jupyter notebook
: 1605940281:0;pip3 install jupyter-tabnine --chi
: 1605940285:0;pip3 install jupyter-tabnine --user
: 1605940293:0;jupyter nbextension install --py jupyter_tabnine --user
: 1605940307:0;jupyter-tabnine
: 1605940643:0;clear
: 1605940665:0;which python3
: 1605940673:0;python3
: 1605942885:0;pip3 install seaborn
: 1605942908:0;which python3
: 1605946048:0;git s
: 1605946053:0;git pull origin staging
: 1605946059:0;git s
: 1605947071:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605948861:0;export | CONFI
: 1605948866:0;export | grep CON
: 1605948908:0;git a .
: 1605948917:0;git cm "added frequency apis"
: 1605948918:0;git s
: 1605948921:0;git checkout develop
: 1605948937:0;git pull origin develop
: 1605949288:0;cd prile/batch_processing/worker/commands/k8s
: 1605949371:0;argo
: 1605949594:0;git s
: 1605949620:0;curl -sLO https://github.com/argoproj/argo/releases/download/v2.11.7/argo-linux-amd64.gz
: 1605950798:0;ls
: 1605950933:0;[200~gunzip argo-linux-amd64.gz~
: 1605950940:0;[200~gargo-linux-amd64.gz~
: 1605950948:0;gunzip argo-linux-amd64.gz
: 1605950957:0;chmod +x argo-linux-amd64
: 1605950965:0;mv ./argo-linux-amd64 /usr/local/bin/argo
: 1605950974:0;sudo mv ./argo-linux-amd64 /usr/local/bin/argo
: 1605950982:0;argo version
: 1605951036:0;clear
: 1605951593:0;kubectl get po | grep faust
: 1605951618:0;kubectl logs -f stag-faust-adjacency-list-6fb6c9f874-96s9d
: 1605951634:0;kubectl get po | grep faust
: 1605951649:0;kubectl delete po stag-faust-adjacency-list-6fb6c9f874-96s9d
: 1605951685:0;kubectl logs -f stag-faust-profile-update-75d6d485db-m5vpb
: 1605951691:0;kubectl get po | grep faust
: 1605951706:0;kubectl logs -f stag-faust-adjacency-list-6fb6c9f874-dknsp
: 1605951752:0;kubectl logs -f stag-faust-profile-update-75d6d485db-m5vpb
: 1605951763:0;kubectl get po | grep faust
: 1605951824:0;kubectl logs -f stag-faust-adjacency-list-6fb6c9f874-dknsp
: 1605951967:0;kubectl get po | grep faust
: 1605951976:0;kubectl logs -f stag-faust-profile-update-75d6d485db-m5vpb
: 1605952106:0;kubectl get po | grep faust
: 1605952114:0;kubectl logs -f faust-profile-update-746bb5868d-c2ptl
: 1605952277:0;kubectl get po | grep faust
: 1605952286:0;kubectl logs -f stag-faust-profile-update-75d6d485db-m5vpb
: 1605952337:0;kubectl get po | grep faust
: 1605952351:0;kubectl logs -f stag-faust-profile-update-56cc4b84f8-vv44p
: 1605952740:0;kubectl get po | grep faust
: 1605952753:0;kubectl delete po stag-faust-profile-update-56cc4b84f8-vv44p
: 1605952819:0;kubectl get po | grep faust
: 1605952829:0;kubectl logs -f stag-faust-profile-update-56cc4b84f8-nvbm2
: 1605953239:0;kubectl delete deployment stag-faust-profile-update
: 1605953347:0;git s
: 1605953353:0;cd ..
: 1605953357:0;ls
: 1605953360:0;git s
: 1605953363:0;git cm a .
: 1605953374:0;git cm "config batch bootstrap"
: 1605953375:0;git s
: 1605953406:0;clear
: 1605953412:0;kubectl get po | grep faust
: 1605953422:0;kubectl logs -f stag-faust-conversion-broadcast-5474994d89-dkr2j
: 1605953494:0;kubectl get po | grep faust
: 1605953508:0;kubectl logs -f stag-faust-adjacency-list-6fb6c9f874-dknsp
: 1605953551:0;kubectl get po | grep faust
: 1605953559:0;kubectl logs -f stag-faust-profile-update-998746566-m9dxt
: 1605953750:0;kubectl get po | grep faust
: 1605953757:0;kubectl logs -f stag-faust-adjacency-list-c4d88d46b-8f64f
: 1605953804:0;git s
: 1605953843:0;git a .
: 1605953845:0;git s
: 1605953853:0;cd ..
: 1605953856:0;git a.
: 1605953858:0;git a .
: 1605953870:0;git cm "config batch boot"
: 1605953872:0;git s
: 1605953882:0;git checkout staging
: 1605953883:0;git s
: 1605953902:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1605953932:0;git push origin staging
: 1605954055:0;kubectl get po | grep faust
: 1605954079:0;kubectl logs -f stag-faust-adjacency-list-c4d88d46b-8f64f
: 1605954250:0;kubectl delete deployment stag-faust-adjacency-list
: 1605954260:0;export | grep CONFI
: 1605954273:0;CONFIG_NAMESPACE=eventify/stag
: 1605954274:0;export | grep CONFI
: 1605954549:0;faust -A prile.workflows.adjacency_list.app worker -l info -p 6069
: 1605954751:0;CONFIG_NAMESPACE=eventify/dev
: 1605954755:0;faust -A prile.workflows.adjacency_list.app worker -l info -p 6069
: 1605954771:0;clear
: 1605954774:0;kubectl port-forward svc/consul-ui 8501:80
: 1605955153:0;faust -A prile.workflows.adjacency_list.app worker -l info -p 6069
: 1605955366:0;git s
: 1605955370:0;git a .
: 1605955379:0;git cm "fix adjacency stream"
: 1605955382:0;git push origin staging
: 1605955392:0;git s
: 1606012977:0;		docker-compose up -d
: 1606012989:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606013320:0;kubectl get po | grep faust
: 1606013352:0;kubectl logs -f stag-faust-profile-update-998746566-m9dxt
: 1606013491:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606013539:0;export | grep CONFI
: 1606013913:0;kubectl logs -f stag-faust-profile-update-998746566-m9dxt
: 1606014149:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606020209:0;clear
: 1606020211:0;which python3
: 1606020427:0;which pip3
: 1606021920:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606022365:0;which python3
: 1606022444:0;ls
: 1606022445:0;pwd
: 1606022460:0;ls
: 1606022463:0;ls -la
: 1606022468:0;cd .python
: 1606022469:0;ls
: 1606022470:0;cd bin
: 1606022471:0;ls
: 1606022476:0;./activate
: 1606022482:0;sudo ./activate
: 1606022492:0;ls -la
: 1606022509:0;./activate
: 1606022519:0;sudo ./activate
: 1606095928:0;		docker-compose up -d
: 1606095942:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606096296:0;git pull origin staging
: 1606096326:0;git s
: 1606096347:0;clear
: 1606096349:0;git s
: 1606096351:0;clear
: 1606096537:0;kubectl get po | grep faust
: 1606096547:0;kubectl logs -f stag-faust-adjacency-list-6bcdf5649b-n2c42
: 1606096573:0;kubectl get po | grep faust
: 1606096583:0;kubectl logs -f faust-events-campaign-84649d8464-ppr7b
: 1606096633:0;kubectl logs -f stag-faust-profile-update-998746566-m9dxt
: 1606097044:0;ls
: 1606097045:0;ls -la
: 1606097054:0;cat .ssh
: 1606097061:0;cd .ssh
: 1606097061:0;;s
: 1606097062:0;ls
: 1606097065:0;cd ..
: 1606097114:0;ls
: 1606097140:0;cd ~/.ssh
: 1606097141:0;ls
: 1606097171:0;cat id_rsa.pub
: 1606097211:0;ls
: 1606097212:0;clear
: 1606097498:0;ssh -i ~/.ssh/id_rsa root@10.110.1.5
: 1606098609:0;kubectl logs -f faust-events-campaign-84649d8464-ppr7b
: 1606098789:0;kubectl get po | grep faust
: 1606098810:0;kubectl logs -f stag-faust-session-update-598bcffd64-4tng2
: 1606098856:0;kubectl logs -f stag-faust-reach-goal-555f94899d-698n6
: 1606099363:0;[
: 1606101509:0;git s
: 1606102241:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606102287:0;export | grep CONFI
: 1606102313:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606102337:0;stag_api
: 1606102357:0;kubectl get po | grep fast
: 1606102372:0;kubectl logs -f stag-fast-api-event-processing-6b89c6d846-fdtb2
: 1606102376:0;kubectl logs -f stag-fast-api-event-processing-6bdd67b9bb-9pxmd
: 1606102566:0;git s
: 1606103495:0;clear
: 1606104161:0;kubectl get po | grep fast
: 1606104167:0;kubectl get po | grep faust
: 1606104191:0;git cm "remove import unnecessary\
"
: 1606104205:0;git s
: 1606104208:0;git a .
: 1606104214:0;git cm "add code"
: 1606104215:0;git s
: 1606104219:0;kubectl logs -f stag-faust-segments-users-update-56ccbb4fbd-69kcf
: 1606104309:0;kubectl logs -f stag-faust-segments-users-update-56ccbb4fbd-69kcf | grep 1kfsqLxYc9PfwmKGckz3tOyHJki
: 1606105127:0;clear
: 1606107454:0;git pull origin staging
: 1606107862:0;clear
: 1606116440:0;kubectl logs -f stag-faust-reach-goal-555f94899d-698n6
: 1606116826:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606117064:0;clear
: 1606120513:0;kubectl get po | grep faust
: 1606120527:0;kubectl logs -f stag-faust-profile-update-998746566-m9dxt
: 1606121933:0;kubectl get po | grep faust
: 1606121943:0;kubectl logs -f stag-faust-segments-users-update-56ccbb4fbd-69kcf
: 1606121982:0;kubectl logs -f stag-faust-segments-users-update-56ccbb4fbd-69kcf | grep 1kfy2QwcnLlO3fIP3qqwhvpSgaW
: 1606122013:0;kubectl delete deployment stag-faust-segments-users-update-56ccbb4fbd-69kcf
: 1606122024:0;kubectl delete deployment stag-faust-segments-users-update
: 1606122028:0;kubectl get po | grep faust
: 1606122104:0;kubectl logs -f faust-segments-users-update-cc8948c58-hvf48
: 1606122157:0;kubectl logs -f faust-segments-users-update-cc8948c58-hvf48 | grep faust-segments-users-update-cc8948c58-hvf48
: 1606122169:0;kubectl logs -f faust-segments-users-update-cc8948c58-hvf48
: 1606122362:0;kubectl get po | grep faust
: 1606122494:0;export | grep CONFI
: 1606122498:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1606122678:0;kubectl delete deployment stag-faust-profile-update-998746566-m9dxt
: 1606122682:0;kubectl delete deployment stag-faust-profile-update
: 1606122698:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1606122720:0;kubectl delete deployment stag-faust-profile-update-998746566-m9dxt
: 1606122724:0;kubectl get po | grep faust
: 1606122741:0;kubectl delete deployment stag-faust-profile-update
: 1606122744:0;kubectl get po | grep faust
: 1606122758:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1606123208:0;clear
: 1606123210:0;kubectl get po | grep faust
: 1606123872:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1606123890:0;git cm "remove import unnecessary\
"
: 1606123896:0;git s
: 1606123900:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606125669:0;git a .
: 1606125807:0;kubectl get po | grep faust
: 1606125830:0;kubectl logs -f stag-faust-conversion-broadcast-5474994d89-dkr2j
: 1606126865:0;kubectl get po | grep faust
: 1606126885:0;kubectl delete deployment stag-faust-conversion-broadcast
: 1606126891:0;kubectl get po | grep faust
: 1606126909:0;kubectl delete deployment stag-faust-events-campaign
: 1606126942:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1606126949:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6068
: 1606126963:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1606126970:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6069
: 1606128882:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6068
: 1606129021:0;clear
: 1606129114:0;git a .
: 1606129141:0;git cm "fixed event campaign convert to dict format"
: 1606129143:0;git s
: 1606129206:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6068
: 1606131824:0;git clone https://github.com/5cr1pt/GitCracken.git
: 1606131833:0;cd GitCracken/GitCracken
: 1606131863:0;yarn 
: 1606131870:0;node install
: 1606131877:0;ls
: 1606131890:0;node
: 1606131936:0;curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -\
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
: 1606131947:0;sudo apt update && sudo apt install yarn
: 1606131983:0;yarn --version
: 1606131992:0;yarn install
: 1606132012:0;yarn build
: 1606132021:0;node dist/bin/gitcracken.js patcher
: 1606132142:0;clear
: 1606132158:0;sudo snap remove gitkraken
: 1606132296:0;ls
: 1606132297:0;cd 
: 1606132299:0;ls
: 1606132303:0;cd Do
: 1606132308:0;cd Downloads
: 1606132308:0;ls
: 1606132319:0;ls -la
: 1606132349:0;sudo dpkg -i gitkraken-amd64.deb
: 1606132356:0;ls
: 1606132399:0;cd ..
: 1606132400:0;ls
: 1606132425:0;git stash save 'fix get user sample not match str and num'
: 1606132428:0;ls
: 1606132429:0;clear
: 1606132492:0;git clone https://github.com/5cr1pt/GitCracken.git
: 1606132499:0;cd GitCracken/GitCracken/
: 1606132503:0;yarn install
: 1606132508:0;yarn build
: 1606132515:0;node dist/bin/gitcracken.js patcher
: 1606132537:0;sudo node dist/bin/gitcracken.js patcher
: 1606132627:0;where gitkraken
: 1606132752:0;node -v
: 1606132757:0;yarn -v
: 1606132840:0;clear
: 1606132853:0;node dist/bin/gitcracken.js patcher\

: 1606132860:0;sudo node dist/bin/gitcracken.js patcher\

: 1606133095:0;\
tree
: 1606133114:0;node -v
: 1606133119:0;yarn -v
: 1606140457:0;sudo apt-get remove gitkraken
: 1606140464:0;ls
: 1606140473:0;clear
: 1606140476:0;gitkraken
: 1606140505:0;sudo apt-get purge gitkraken
: 1606140523:0;ls
: 1606140542:0;sudo apt-get autoremove
: 1606140578:0;ls -la
: 1606140602:0;rm -R .gitkraken
: 1606140605:0;ls -la
: 1606140627:0;ls -la | grep git
: 1606140693:0;cd Downloads
: 1606140864:0;ls
: 1606140867:0;sudo dpkg -i gitkraken-amd64.deb
: 1606140920:0;cd GitCracken/GitCracken/
: 1606140930:0;yarn install
: 1606140934:0;yarn build
: 1606140944:0;node dist/bin/gitcracken.js patcher
: 1606140949:0;sudo node dist/bin/gitcracken.js patcher
: 1606182938:0;cd ..
: 1606182941:0;ls
: 1606182942:0;clear
: 1606182947:0;kubectl get po | grep CONFI
: 1606182981:0;		docker-compose up -d
: 1606182997:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606183008:0;kubectl get po | grep CONFI
: 1606183024:0;kubectl get po | grep faust
: 1606183044:0;kubectl logs -f stag-faust-events-campaign-558d654d8d-dlt2q
: 1606183143:0;git checkout master
: 1606183147:0;git merge staging
: 1606183225:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606183321:0;git s
: 1606183346:0;git push origin master
: 1606183386:0;git pull origin master
: 1606183416:0;git s
: 1606183462:0;git push origin master
: 1606183472:0;git s
: 1606183615:0;clear
: 1606183631:0;kubectl get po | grep faust
: 1606183721:0;kubectl logs -f stag-faust-profile-update-7699cf74b-7s4zj
: 1606184068:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606184150:0;kubectl get po | grep fast
: 1606184172:0;kubectl logs -f fast-api-event-processing-68675d696-5pgxf
: 1606184186:0;kubectl get po | grep fast
: 1606184191:0;kubectl get po | grep faust
: 1606184229:0;kubectl logs -f faust-conversion-broadcast-5686dcb9d7-vjcch
: 1606184400:0;git checkout staging
: 1606184432:0;git checkout develop
: 1606184436:0;git merge staging
: 1606184469:0;git checkout staging
: 1606184480:0;git merge develop
: 1606184503:0;git push origin staging
: 1606184534:0;kubectl get po | grep faust
: 1606184560:0;kubectl logs -f faust-conversion-broadcast-7d6b75f855-4mnrh
: 1606184634:0;kubectl get po | grep faust
: 1606184646:0;kubectl logs -f faust-profile-update-576b975676-qvpgg
: 1606184650:0;clear
: 1606184866:0;git checkout -b segment_analytics_histogram
: 1606184874:0;git s
: 1606186404:0;kubectl get po | grep faust
: 1606186452:0;kubectl logs faust-profile-update-576b975676-qvpgg
: 1606186465:0;kubectl describe faust-profile-update-576b975676-qvpgg
: 1606186471:0;kubectl describe pod faust-profile-update-576b975676-qvpgg
: 1606186841:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606187522:0;kubectl get po | grep faust
: 1606188587:0;kubectl logs -f stag-faust-profile-update-7699cf74b-7s4zj
: 1606189175:0;kubectl get po | grep faust
: 1606189189:0;kubectl logs -f stag-faust-session-update-86b4f77d5b-kbsm9
: 1606189203:0;kubectl get po | grep faust
: 1606189263:0;kubectl delete deployment stag-faust-conversion-broadcast stag-faust-events-campaign stag-faust-profile-update stag-faust-reach-goal stag-faust-segments-users-update stag-faust-session-update
: 1606189293:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6066
: 1606189308:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6067
: 1606189331:0;faust -A prile.workflows.profile_update.app worker -l info -p 6068
: 1606189344:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6069
: 1606189359:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6070
: 1606189375:0;faust -A prile.workflows.session_updated.app worker -l info -p 6071
: 1606189607:0;faust -A prile.workflows.profile_update.app worker -l info -p 6068
: 1606192288:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606201461:0;git s
: 1606201549:0;git a .
: 1606201552:0;git s
: 1606201704:0;git commit -m "2 endpoints customer universal id mapping"
: 1606201705:0;git s
: 1606201725:0;git checkout -b customer_identity
: 1606201838:0;git checkout staging
: 1606201846:0;git merge customer_identity
: 1606201873:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1606201882:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6073
: 1606201929:0;git pull origin staging
: 1606201974:0;git push origin staging
: 1606202017:0;git s
: 1606202039:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1606202045:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6073
: 1606203229:0;git s
: 1606203231:0;git a .
: 1606203252:0;git cm "refine reach goal stream processor"
: 1606203253:0;git s
: 1606203257:0;git push origin staging
: 1606203330:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606204235:0;kubectl get po | grep faust
: 1606204367:0;clear
: 1606204400:0;git s
: 1606204421:0;git checkout -b segment_analytic_histogram
: 1606204427:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606207361:0;git s
: 1606207388:0;git stash save "segment analytics"
: 1606207390:0;git s
: 1606207402:0;git checkout staging
: 1606207404:0;git s
: 1606207519:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606213966:0;git s
: 1606213967:0;git a .
: 1606213988:0;git cm "fixed get campaign metric table have filter name"
: 1606213988:0;git s
: 1606214008:0;git push origin staging
: 1606214016:0;git s
: 1606214017:0;clear
: 1606214060:0;git s
: 1606217016:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606218052:0;git s
: 1606218056:0;git a .
: 1606218175:0;git cm "[staging] fixed get total click time series count unique anonymous"
: 1606218177:0;git s
: 1606218183:0;git push origin staging
: 1606218342:0;git checkout segment_analytic_histogram
: 1606218360:0;git pull origin staging
: 1606218507:0;clear
: 1606218509:0;git s
: 1606232188:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606232195:0;		docker-compose up -d
: 1606232205:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606232387:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606269924:0;		docker-compose up -d
: 1606269946:0;git s
: 1606269951:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606269966:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606269981:0;kubectl get po | grep faust
: 1606270009:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1606270025:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1606270044:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1606270069:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1606270084:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6070
: 1606270103:0;faust -A prile.workflows.session_updated.app worker -l info -p 6071
: 1606270160:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1606270326:0;git checkout master
: 1606270330:0;git merge staging
: 1606270341:0;git s
: 1606270415:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606270442:0;git push origin master
: 1606270505:0;kubectl get po | grep faust
: 1606270536:0;kubectl logs -f stag-faust-adjacency-list-9bd8c88c8-l8j6f
: 1606270587:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1606270599:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6072
: 1606271182:0;git s
: 1606271218:0;git checkout segment_analytic_histogram
: 1606271219:0;git s
: 1606271498:0;git pop stash 
: 1606271515:0;git stash pop
: 1606276290:0;git s
: 1606276322:0;git cm "added more metric to histogram api"
: 1606276323:0;git a .
: 1606276324:0;git cm "added more metric to histogram api"
: 1606276462:0;git checkout staging
: 1606276499:0;git cherry-pick ce13ba79dd13dfeb48baaa29fa288fba32e91df9
: 1606276553:0;git s
: 1606276584:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606276679:0;git push origin staging
: 1606276686:0;git 
: 1606294300:0;git checkout master
: 1606294304:0;git s
: 1606294315:0;git a .
: 1606294344:0;git cm "[staging] remove debug line"
: 1606294345:0;git s
: 1606294349:0;git push origin staging
: 1606294358:0;git checkout master
: 1606294362:0;git merge staging
: 1606294369:0;git push origin master
: 1606294382:0;git checkout staging
: 1606294619:0;kubectl get po | grep fast
: 1606294661:0;kubectl logs -f stag-fast-api-event-processing-5d8c8cb676-4vgc8
: 1606294715:0;kubectl get po | grep faust
: 1606294860:0;clear
: 1606295105:0;kubectl get po | grep faust
: 1606295126:0;kubectl get po | grep fast
: 1606295171:0;kubectl logs -f stag-faust-events-campaign-666dd45844-5n575
: 1606295265:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606295271:0;docker ps
: 1606295308:0;kubectl get po | grep faust
: 1606295324:0;kubectl logs -f stag-faust-events-campaign-666dd45844-5n575
: 1606295372:0;kubectl get po | grep faust
: 1606295401:0;kubectl logs -f stag-faust-conversion-broadcast-7cdd99dc55-28gz7
: 1606295431:0;kubectl get po | grep faust
: 1606295450:0;kubectl logs -f stag-faust-conversion-broadcast-7cdd99dc55-28gz7
: 1606295510:0;kubectl get po | grep faust
: 1606295520:0;kubectl delete po stag-faust-conversion-broadcast-7cdd99dc55-28gz7
: 1606295532:0;kubectl delete po stag-faust-adjacency-list-59f7b8c874-ffd4k
: 1606295578:0;kubectl delete po stag-faust-events-campaign-666dd45844-5n575
: 1606295587:0;kubectl get po | grep faust
: 1606295736:0;kubectl get svc
: 1606295762:0;kubectl get deployment
: 1606295812:0;kubectl describe deployment stag-faust-events-campaign-666dd45844-5n575
: 1606295857:0;kubectl describe deployment stag-faust-events-campaign
: 1606295902:0;kubectl get po | grep faust
: 1606296409:0;clear
: 1606296412:0;kubectl get po | grep faust
: 1606296439:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606296445:0;kubectl get po | grep faust
: 1606296525:0;kubectl logs -f stag-faust-events-campaign-56f5d85b65-vnpx2
: 1606296555:0;kubectl delete po stag-faust-events-campaign-56f5d85b65-vnpx2
: 1606296680:0;kubectl get po | grep faust
: 1606296805:0;kubectl logs -f stag-faust-conversion-broadcast-6694ff47c5-hr9t2
: 1606296929:0;kubectl get po | grep faust
: 1606296974:0;kubectl logs -f stag-faust-profile-update-75445cfdc8-kxzw2
: 1606297030:0;clear
: 1606297063:0;kubectl get po | grep faust
: 1606297104:0;kubectl logs -f stag-faust-profile-update-75445cfdc8-kxzw2
: 1606297108:0;kubectl get po | grep faust
: 1606297115:0;kubectl logs -f stag-faust-events-campaign-56f5d85b65-42g72
: 1606298422:0;clear
: 1606298489:0;git s
: 1606298496:0;git a .
: 1606298530:0;git cm "[staging] rename campaign filter mapping"
: 1606298531:0;git s
: 1606298559:0;git push origin staging
: 1606298891:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606299818:0;cd Downloads
: 1606299819:0;ls
: 1606299826:0;cd GitCracken/GitCracken/
: 1606299832:0;yarn install
: 1606299840:0;yarn build
: 1606299848:0;node dist/bin/gitcracken.js patcher
: 1606299856:0;sudo node dist/bin/gitcracken.js patcher
: 1606356399:0;		docker-compose up -d
: 1606356410:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606356421:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606356472:0;git s
: 1606356534:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1606356549:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1606356560:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1606356570:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1606356581:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6068
: 1606356590:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6069
: 1606356670:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6066
: 1606356677:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6070
: 1606356696:0;faust -A prile.workflows.session_updated.app worker -l info -p 6071
: 1606356702:0;git s
: 1606356789:0;kubectl get po | grep faust
: 1606356827:0;git checkout master
: 1606356830:0;git merge staging
: 1606356862:0;git push origin master
: 1606356945:0;git s
: 1606356949:0;git push origin master
: 1606356988:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606357002:0;git push origin master
: 1606357597:0;git checkout staging
: 1606357621:0;git checkout -b fix_campaign_filter
: 1606359537:0;		docker-compose up -d
: 1606359548:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606359568:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1606359599:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1606359619:0;faust -A prile.workflows.profile_update.app worker -l info -p 6068
: 1606359625:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1606359641:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6069
: 1606359660:0;faust -A prile.workflows.segments_users_update.app worker -l info -p 6070
: 1606359674:0;faust -A prile.workflows.session_updated.app worker -l info -p 6071
: 1606361607:0;kubectl get po | grep faust
: 1606366337:0;git s
: 1606366342:0;git a .
: 1606366397:0;git cm "[fix_campaign_filter] modify filter in api get campaign data, testing"
: 1606366404:0;git push origin fix_campaign_filter
: 1606366508:0;git s
: 1606366510:0;clear
: 1606366515:0;git push origin fix_campaign_filter
: 1606366630:0;ssh -T -p 443 git@ssh.github.com
: 1606366654:0;git push origin fix_campaign_filter
: 1606366701:0;nano ~/.ssh/config
: 1606366708:0;git push origin
: 1606366717:0;git push origin fix_campaign_filter
: 1606366727:0;sudo git push origin fix_campaign_filter
: 1606366767:0;git s
: 1606366775:0;git push origin fix_campaign_filter
: 1606366837:0;nano ~/.ssh/config
: 1606366875:0;ssh -T git@github.com
: 1606366903:0;git s 
: 1606366981:0;git clone git@github.com:primedata-ai/event-processing.git
: 1606366987:0;ls
: 1606368945:0;		docker-compose up -d
: 1606368956:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606368983:0;git s
: 1606368989:0;git tree
: 1606368999:0;git push origin fix_campaign_filter
: 1606371624:0;uvicorn main:app --reload --host 0.0.0.0 --port 8889
: 1606371951:0;git a .
: 1606371952:0;git cm 
: 1606371989:0;git cm "fixed filter key in ptrais"
: 1606371990:0;git s
: 1606371995:0;git push origin fix_campaign_filter
: 1606377354:0;git s
: 1606377358:0;git checkout staging
: 1606377363:0;git merge fix_campaign_filter
: 1606377372:0;git s
: 1606377427:0;git stash save 'modify how to caculate campaign uplift revenue per customer'
: 1606377428:0;git s
: 1606377436:0;git checkout staging
: 1606377443:0;git merge fix_campaign_filter
: 1606377450:0;git stash pop
: 1606377452:0;git s
: 1606377650:0;git a .
: 1606377692:0;git cm "modified campaign uplift avg revenue per customer"
: 1606377695:0;git s
: 1606377713:0;git push origin staging
: 1606379301:0;git s
: 1606379415:0;git a .
: 1606379453:0;git cm "added to start of func to get num click time series"
: 1606379458:0;git push origin staging
: 1606379829:0;git s
: 1606380190:0;git tree
: 1606380731:0;git s
: 1606380737:0;git status
: 1606380805:0;kubectl get po | grep faust
: 1606380813:0;kubectl get po | grep fast
: 1606380835:0;kubectl logs -f stag-fast-api-event-processing-7d8bb85484-chpdl
: 1606380849:0;kubectl delete deployment stag-fast-api-event-processing-7d8bb85484-chpdl
: 1606380854:0;kubectl delete deployment stag-fast-api-event-processing
: 1606380878:0;kubectl get po | grep fast
: 1606381294:0;kubectl describe stag-fast-api-event-processing-5ff5689944-fm6zz
: 1606381300:0;kubectl describe po stag-fast-api-event-processing-5ff5689944-fm6zz
: 1606381363:0;git s
: 1606382640:0;kubectl get po | grep fast
: 1606386240:0;pwd
: 1606386241:0;clear
: 1606387263:0;kubectl get po | grep fast
: 1606387360:0;clear
: 1606388888:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1606389200:0;git a 
: 1606389203:0;git a .
: 1606389219:0;git cm "fix get campaign uplift"
: 1606389220:0;git s
: 1606389223:0;git push origin staging
: 1606389233:0;git s
: 1606389368:0;clear
: 1606390133:0;git s
: 1606397908:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606397927:0;kubectl get po | grep faust
: 1606397962:0;kubectl logs -f stag-faust-events-campaign-bcbff66f4-s8rk8
: 1606402803:0;kubectl get po | grep faust
: 1606402812:0;kubectl logs -f stag-faust-segments-users-update-54dc6d795c-c6rlp
: 1606441552:0;		docker-compose up -d
: 1606441569:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606441585:0;kubectl get po | grep faust
: 1606441600:0;kubectl logs -f stag-faust-conversion-broadcast-859bfcdd89-ftvx7
: 1606441612:0;git s
: 1606442144:0;it s
: 1606442145:0;git s
: 1606442151:0;git a .
: 1606442186:0;git cm "refine to start of func, api get campaign trending metrics"
: 1606442186:0;git s
: 1606442192:0;git push origin staging
: 1606442325:0;git s
: 1606448193:0;git a .
: 1606448247:0;git cm "refine to start of func for get campaign data time series"
: 1606448279:0;git s
: 1606448282:0;git tree
: 1606448287:0;git push origin staging
: 1606448689:0;git s
: 1606458602:0;git a .
: 1606458658:0;git cm "only return value contain tactic in get campaign performace time series"
: 1606458659:0;git 
: 1606458661:0;git s
: 1606458665:0;git push origin staging
: 1606458730:0;git s
: 1606462892:0;git merge master
: 1606462901:0;git tree
: 1606463197:0;git checkout master
: 1606463199:0;git s
: 1606463207:0;git merge staging
: 1606463208:0;git s
: 1606463215:0;git push origin master
: 1606463224:0;git tree
: 1606463232:0;git push origin master
: 1606464014:0;kubectl get po | grep faust
: 1606465673:0;git s
: 1606465680:0;git stash save
: 1606465681:0;git s
: 1606465684:0;git checkout staging
: 1606465690:0;git stash pop
: 1606465692:0;git s
: 1606465694:0;git a .
: 1606465744:0;git cm "api get campaign performace time serires limit 10"
: 1606465745:0;git s
: 1606465748:0;git push origin staging
: 1606465953:0;kubectl get po | grep faust
: 1606467623:0;git a .
: 1606467656:0;git cm "api campaign performace timeseries add time_stamp to base cols"
: 1606467660:0;git push origin staging
: 1606486478:0;		docker-compose up -d
: 1606486485:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606500729:0;git a .
: 1606500748:0;git cm "coding get campaign table v2"
: 1606500752:0;git push origin staging
: 1606536163:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1606536169:0;		docker-compose up -d
: 1606536176:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606536180:0;		docker-compose up -d
: 1606536186:0;uvicorn main:app --reload --host 0.0.0.0 --port 8888
: 1606558805:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606559604:0;		docker-compose up -d
: 1606559615:0;clear
: 1606559616:0;ls
: 1606559618:0;clear
: 1606572863:0;		docker-compose up -d
: 1606572872:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606613309:0;		docker-compose up -d
: 1606613317:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606699984:0;		docker-compose up -d
: 1606699990:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606699993:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606729535:0;git s
: 1606729568:0;git cm "refactor api get campaign performace time series: calulate metric with sql"
: 1606729572:0;git a .
: 1606729574:0;git cm "refactor api get campaign performace time series: calulate metric with sql"
: 1606729575:0;git s
: 1606729579:0;git tree
: 1606729586:0;git push origin staging
: 1606732029:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606734161:0;git add .
: 1606734175:0;git cm "added more sql calculate metric campaign"
: 1606734180:0;git push origin staging
: 1606735108:0;git a .
: 1606735138:0;git cm "get campaign data time series get top 10"
: 1606735139:0;git s
: 1606735145:0;git push origin staging
: 1606736063:0;git s
: 1606736065:0;git a .
: 1606736090:0;git cm "edited get top 10 campaign ts api"
: 1606736090:0;git s
: 1606736097:0;git push origin staging
: 1606738333:0;git add . 
: 1606738375:0;git commit -m "[stag] order timeseries" 
: 1606738388:0;git push origin stag
: 1606738392:0;git push origin staging
: 1606739545:0;git a .
: 1606739559:0;git cm "mutiple 100 percent"
: 1606739563:0;git push origin staging
: 1606747508:0;		docker-compose up -d
: 1606747515:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606753661:0;git checkout try_for_in_sql
: 1606753665:0;git checkout -b try_for_in_sql
: 1606761463:0;git a .
: 1606761474:0;git cm "filled missing day get campaign ts"
: 1606761475:0;git s
: 1606761484:0;git push origin try_for_in_sql
: 1606762007:0;git a .
: 1606762021:0;git cm "refine to start of func"
: 1606762026:0;git push origin try_
: 1606762029:0;git push origin try_for_in_sql
: 1606793776:0;		docker-compose up -d
: 1606793783:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606793797:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606794450:0;git s
: 1606795694:0;git a .
: 1606795710:0;git cm "refomated code campaign analytics"
: 1606795711:0;git s
: 1606795717:0;git push origin try_for_in_sql
: 1606796913:0;kubectl ps
: 1606796918:0;kubectl get pods
: 1606796926:0;kubectl get pods | grep fast
: 1606806851:0;git a .
: 1606806901:0;git cm "fixed get metric campaign performance for Truong bro"
: 1606806902:0;git s
: 1606806913:0;git checkout staging
: 1606806919:0;git merge try_for_in_sql
: 1606806920:0;git s
: 1606806924:0;git push origin staging
: 1606806981:0;git s
: 1606806985:0;git status
: 1606807078:0;git checkout master
: 1606807082:0;git merge staging
: 1606807083:0;git s
: 1606807092:0;git checkout staging
: 1606807093:0;git s
: 1606807094:0;git tree
: 1606807102:0;git checkout master
: 1606807107:0;git push origin master
: 1606807113:0;git s
: 1606807117:0;git checkout staging
: 1606807118:0;git s
: 1606807172:0;git tree
: 1606815204:0;git s
: 1606817650:0;git a .
: 1606817711:0;git cm "[staging] [CA] expose goal metric for Truong"
: 1606817711:0;git s
: 1606817717:0;git push origin staging
: 1606820103:0;git a . 
: 1606820147:0;git cm "[staging] [CA] fixed campaign performace use function common"
: 1606820148:0;git s
: 1606820153:0;git push origin staging
: 1606822235:0;git a .
: 1606822262:0;git cm "[staging] [CA] supported goals metric time series"
: 1606822266:0;git push origin staging
: 1606822296:0;git s
: 1606823557:0;clear
: 1606823559:0;git s
: 1606825487:0;git a .
: 1606825502:0;git cm "added test for fill missing date func"
: 1606825507:0;git push origin staging
: 1606825604:0;kubectl get po | grep faust
: 1606825615:0;kubectl logs -f stag-faust-profile-update-6fcc4b4fd-pdms7
: 1606825639:0;kubectl get po | grep faust
: 1606825659:0;kubectl logs -f faust-profile-update-75b4b94bf4-mg84f
: 1606825736:0;git s
: 1606825738:0;git a .
: 1606825768:0;git cm "[staging] [CA] refine to start of func"
: 1606825771:0;git push origin staging
: 1606826088:0;git a .
: 1606826110:0;git cm "[staging] [CA] updated campaign sql"
: 1606826237:0;git checkout master
: 1606826240:0;git merge staging
: 1606826243:0;git push origin master
: 1606826263:0;git s
: 1606826264:0;clear
: 1606877622:0;		docker-compose up -d
: 1606877631:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606878325:0;kubectl get po | grep faust
: 1606878334:0;kubectl logs -f stag-faust-profile-update-6fcc4b4fd-pdms7
: 1606878702:0;kubectl get po | grep faust
: 1606878710:0;kubectl logs -f stag-faust-conversion-broadcast-5d59dd8698-kwrgk
: 1606878771:0;kubectl logs -f stag-faust-profile-update-6fcc4b4fd-pdms7
: 1606879452:0;git s
: 1606879457:0;git checkout staging
: 1606880092:0;git checkout master
: 1606880258:0;git checkout staging
: 1606880274:0;git checkout develop
: 1606880281:0;git merge develop
: 1606880286:0;git merge staging
: 1606881493:0;git log
: 1606882991:0;git checkout staging
: 1606884515:0;git checkout develop
: 1606889793:0;kubectl logs -f stag-faust-profile-update-6fcc4b4fd-pdms7
: 1606891555:0;git co
: 1606891566:0;git co -b add_test
: 1606891571:0;git s
: 1606893016:0;clear
: 1606893026:0;kubectl get po | grep faust
: 1606893037:0;kubectl logs -f stag-faust-conversion-broadcast-5d59dd8698-kwrgk
: 1606895085:0;git s
: 1606895116:0;git checkout develop
: 1606895118:0;git s
: 1606895127:0;git checkout add_
: 1606895133:0;git co add_test
: 1606895140:0;git stash save
: 1606895143:0;git s
: 1606895155:0;git co develop
: 1606895707:0;git s
: 1606896098:0;git co add_test
: 1606896752:0;git s
: 1606899135:0;pytest
: 1606899678:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606900275:0;docker ps
: 1606900284:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606900910:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606903800:0;export | grep CONFI
: 1606904648:0;ls
: 1606904652:0;git s
: 1606907329:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606919562:0;git s
: 1606919589:0;git 
: 1606919591:0;git a .
: 1606919608:0;git cm "config and added test for apis"
: 1606919615:0;git push origin add_test
: 1606920264:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1606920330:0;git s
: 1606920333:0;git a .
: 1606920352:0;git cm "swith to start of day get click time series"
: 1606920353:0;git s
: 1606920366:0;git checkout master
: 1606920385:0;git merge add_test
: 1606920456:0;git push origin master
: 1606961111:0;		docker-compose up -d
: 1606961123:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1606962110:0;docker ps
: 1606962126:0;		docker-compose up -d
: 1606962131:0;docker ps
: 1606962144:0;docker exec -it efa7b517aa29 /bin/bash
: 1606962199:0;git checkout staging
: 1606962200:0;git s
: 1606962224:0;git merge master
: 1606962238:0;git push origin staging
: 1606962247:0;git s
: 1606962249:0;clear
: 1606962667:0;kubectl get pods
: 1606962672:0;kubectl get pods | grep redis
: 1606963252:0;kubectl get po | faust
: 1606963256:0;kubectl get po | grep faust
: 1606963270:0;kubectl logs -f faust-reach-goal-5f4fbbf754-z7vkt
: 1606963676:0;kubectl get po | grep faust
: 1606963683:0;kubectl logs -f stag-faust-reach-goal-5989496555-5gcgb
: 1606970135:0;git s
: 1606970185:0;git cm "switch Frequency metric = total order for demo"
: 1606970186:0;git s
: 1606970188:0;git a .
: 1606970190:0;git cm "switch Frequency metric = total order for demo"
: 1606970192:0;git s
: 1606970201:0;git push origin staging
: 1606970239:0;git s
: 1606972218:0;ti s
: 1606972220:0;git s
: 1606972225:0;git a .
: 1606972261:0;git cm "cheat data: Order mementum and campaign engagement score"
: 1606972262:0;git s
: 1606972267:0;git push origin staging
: 1606972274:0;git s
: 1606978212:0;kubectl get po | grep faast
: 1606978215:0;kubectl get po | grep fast
: 1606978293:0;ls
: 1606978295:0;clear
: 1606978775:0;gu ts
: 1606978777:0;git s
: 1606978810:0;kubectl get po | grep faust
: 1606978820:0;kubectl logs -f stag-faust-segments-users-update-58fcff7f7-2nxwk
: 1606981124:0;git s
: 1606981260:0;git a .
: 1606981313:0;git cm "switched get segment total user time series"
: 1606981313:0;git s
: 1606981318:0;git push origin staging
: 1606981523:0;kubectl get po | grep faust
: 1606981530:0;kubectl get po | grep faast
: 1606981532:0;kubectl get po | grep fast
: 1606982029:0;git checkout master
: 1606982035:0;git s
: 1606982058:0;git checkout master
: 1606982060:0;git s
: 1606982071:0;git merge staging
: 1606982072:0;git s
: 1606982255:0;kubectl get po | grep faust
: 1606982266:0;kubectl get po | grep fast
: 1606982312:0;git push origin master
: 1606982319:0;git s
: 1606982322:0;git treee
: 1606982325:0;git tree
: 1606982387:0;git branch -d add_test
: 1606982389:0;git s
: 1606983939:0;git checkout staging
: 1606983940:0;git s
: 1606983942:0;git a .
: 1606983981:0;git cm "changed segment_user -> segment user final v"
: 1606983982:0;git s
: 1606983986:0;git push origin staging
: 1606983999:0;git checkout master
: 1606984001:0;git merge staging
: 1606984122:0;git s
: 1606984131:0;git push origin master
: 1606984144:0;git checkout master
: 1606984148:0;git checkout staging
: 1606984151:0;git push origin staging
: 1606984202:0;git s
: 1606984357:0;kubectl get po | grep faust
: 1606984360:0;kubectl get po | grep fast
: 1606985423:0;ls
: 1606985424:0;clear
: 1606987460:0;kubectl get po | grep faust
: 1606987540:0;kubectl logs -f faust-conversion-broadcast-57767786cd-qtcs6
: 1606987592:0;kubectl get po | grep faust
: 1606987609:0;kubectl delete deployment faust-conversion-broadcast-57767786cd-qtcs6
: 1606987614:0;kubectl delete deployment faust-conversion-broadcast
: 1606987644:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1606987668:0;kubectl logs -f faust-conversion-broadcast-57767786cd-qtcs6
: 1606988026:0;kubectl get po | grep fausts
: 1606988035:0;export | grep CONFI
: 1606988043:0;export CONFIG_NAMESPACE=eventify/prod
: 1606988053:0;export | grep CONFI
: 1606988055:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1606990089:0;git s
: 1606990091:0;git a .
: 1606990110:0;git cm "fixed path campaign in conversion process"
: 1606990116:0;git push origin staging
: 1606990134:0;git checkout master
: 1606990138:0;git merge staging
: 1606990142:0;git push origin master
: 1606990190:0;git s
: 1606990393:0;kubectl get po | grep faust
: 1606990595:0;kubectl logs -f faust-conversion-broadcast-f855b6859-zd6kg
: 1607046472:0;		docker-compose up -d
: 1607046478:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607054920:0;git s
: 1607054926:0;git checkout staging
: 1607054928:0;git s
: 1607055199:0;git a .
: 1607055299:0;git cm "fixed conversion rate sql, case clicks equal 0"
: 1607055300:0;git s
: 1607055309:0;git push origin staging
: 1607055454:0;export | grep CONF
: 1607055461:0;clear
: 1607055930:0;git a .
: 1607055957:0;git cm "renamed module"
: 1607055958:0;git s
: 1607059178:0;git s 
: 1607059187:0;git a .
: 1607059200:0;git cm "restructure tests folder"
: 1607059204:0;git push origin staging
: 1607062717:0;git s
: 1607062740:0;clear
: 1607067903:0;git s
: 1607067916:0;git co attribution
: 1607067920:0;git a .
: 1607067930:0;git stash "testing"
: 1607067937:0;git stash save "testing"
: 1607067938:0;git s
: 1607067942:0;git co attribution
: 1607068028:0;export | grep CON
: 1607068031:0;export | grep CONFI
: 1607068056:0;python3 -m prile.analytics.attribution.pipeline
: 1607068350:0;git pull origin attribution
: 1607069263:0;git s
: 1607069324:0;git a .
: 1607069389:0;git cm "added converion path model"
: 1607069402:0;git pull origin attribution
: 1607069412:0;git s
: 1607073131:0;git merge master
: 1607073141:0;git s
: 1607073339:0;git a .
: 1607073340:0;git s
: 1607073347:0;git cm "Chi merge with master"
: 1607073348:0;git s
: 1607081813:0;git tree
: 1607133456:0;git s
: 1607133460:0;git a .
: 1607133509:0;git cm "expose conversion path api"
: 1607133511:0;git s
: 1607133552:0;git pull origin attribution
: 1607133744:0;git a .
: 1607133863:0;git cm "Chi merged with origin"
: 1607133864:0;git s
: 1607134110:0;git push origin attribution
: 1607135138:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607135154:0;		docker-compose up -d
: 1607135160:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607135177:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607135800:0;git s
: 1607135852:0;git cm "rename module and added test api endpoint for attribution"
: 1607135859:0;git push origin attribution
: 1607135872:0;git checkout staging
: 1607135889:0;git a .
: 1607135891:0;git cm "rename module and added test api endpoint for attribution"
: 1607135893:0;git s
: 1607135926:0;git push origin attribution
: 1607135944:0;git checkout staging
: 1607135948:0;git merge attribution
: 1607136459:0;git s
: 1607136613:0;git a .
: 1607136614:0;git s
: 1607136623:0;git cm "merged staing with attribution"
: 1607136624:0;git s
: 1607136628:0;git push origin staging
: 1607136641:0;git s
: 1607137234:0;clear
: 1607152765:0;export | grep CONFI
: 1607153886:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1607155791:0;git a .
: 1607155817:0;git cm "saved events conversion to db"
: 1607155818:0;git s
: 1607156617:0;git 
: 1607156618:0;git s
: 1607222933:0;		docker-compose up -d
: 1607222940:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607225570:0;git s
: 1607226014:0;git co -b rfm_metrics
: 1607226018:0;git s
: 1607298666:0;git a .
: 1607298668:0;git s
: 1607298682:0;git cm "modify rfm metrics"
: 1607298683:0;git s
: 1607305162:0;		docker-compose up -d
: 1607305171:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607305436:0;kubectl get po | grep faust
: 1607305447:0;kubectl logs -f stag-faust-profile-update-6fcc4b4fd-pdms7
: 1607305611:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607305620:0;kubectl logs -f stag-faust-profile-update-6fcc4b4fd-pdms7
: 1607305751:0;kubectl get po | grep faust
: 1607305765:0;kubectl delete deployment stag-faust-profile-update
: 1607305872:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1607306808:0;git s
: 1607306823:0;git cm "add cron job profile udpate"
: 1607306826:0;git co staging
: 1607306830:0;git s
: 1607306841:0;git a .
: 1607306843:0;git cm "add cron job profile udpate"
: 1607306847:0;git checkout staging
: 1607306847:0;git s
: 1607309533:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607309548:0;export | grep CONF
: 1607309556:0;CONFIG_NAMESPACE=eventify/prod
: 1607309558:0;export | grep CONF
: 1607309564:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607309814:0;git s
: 1607309832:0;git cm "fixed conversion rate sql, case clicks equal 0"
: 1607309833:0;git s
: 1607309837:0;git a .
: 1607309839:0;git cm "fixed conversion rate sql, case clicks equal 0"
: 1607309840:0;git s
: 1607309845:0;git push origin staging
: 1607309861:0;git s
: 1607309866:0;git push origin staging
: 1607309889:0;git co master
: 1607309892:0;git merge staging
: 1607309901:0;git push origin master
: 1607310033:0;git co staging
: 1607313943:0;kubectl get po | grep faust
: 1607313992:0;kubectl delete deployment stag-faust-conversion-broadcast
: 1607314004:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1607314078:0;kubectl get po | grep faust
: 1607314092:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1607315409:0;git a .
: 1607315443:0;git cm "forward profile update conversion to ptrait event"
: 1607315443:0;git s
: 1607316939:0;faust -A prile.workflows.reach_goal.app worker -l info -p 6067
: 1607316969:0;faust -A prile.workflows.rfm_update.app worker -l info -p 6067
: 1607317017:0;export | grep CONF
: 1607317045:0;CONFIG_NAMESPACE=eventify/dev
: 1607317048:0;export | grep CONF
: 1607317051:0;faust -A prile.workflows.rfm_update.app worker -l info -p 6067
: 1607326203:0;faust -A prile.workflows.profile_update.app worker -l info -p 6067
: 1607326208:0;faust -A prile.workflows.profile_update.app worker -l info -p 6068
: 1607326237:0;kubectl get po | grep faust
: 1607326251:0;faust -A prile.workflows.profile_update.app worker -l info -p 6069
: 1607326302:0;git s
: 1607326347:0;git a .
: 1607326365:0;git cm "forward rfm to profile update and ptrait event topic"
: 1607326366:0;git s
: 1607326548:0;faust -A prile.workflows.rfm_update.app worker -l info -p 6067
: 1607329309:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607329936:0;git a .
: 1607330234:0;git cm "expose get customer ptraits list"
: 1607330235:0;git s
: 1607330239:0;git push origin staging
: 1607332214:0;cd prile/batch_processing/worker/commands/k8s
: 1607332956:0;gti s
: 1607332957:0;git s
: 1607333657:0;kubectl port-forward svc/consul-ui 8501:80
: 1607333701:0;git s
: 1607333771:0;git a .
: 1607333810:0;gti cm "config env argo and refactor rfm"
: 1607333811:0;git s
: 1607333821:0;git push origin staging
: 1607333854:0;git s
: 1607333863:0;git a .
: 1607333864:0;git s
: 1607333889:0;git a .
: 1607333910:0;git cm "config env argo and refactor rfm processor"
: 1607333911:0;git 
: 1607333913:0;git s
: 1607333918:0;git push origin staging
: 1607333940:0;git s
: 1607334110:0;cd prile/batch_processing/worker/commands/k8s
: 1607336070:0;git pull origin staging
: 1607336389:0;git s 
: 1607336688:0;git s
: 1607336707:0;git cm "restructure batch processing folder"
: 1607336707:0;git s
: 1607336711:0;git a .
: 1607336714:0;git cm "restructure batch processing folder"
: 1607336715:0;git s
: 1607336719:0;git push origin staging
: 1607337656:0;python3 -m prile.batch_processing.pipelines.rfm.py
: 1607337805:0;python3 -m prile.batch_processing.pipelines.rfm
: 1607338213:0;git s 
: 1607338226:0;git cm "updated rfm pipeline"
: 1607338229:0;git a .
: 1607338230:0;git cm "updated rfm pipeline"
: 1607338231:0;git s
: 1607338234:0;git push origin staging
: 1607338504:0;git s
: 1607338568:0;python3 -m prile.analytics.attribution.process.pipeline
: 1607338604:0;python3 -m prile.batch_processing.pipelines.attribution
: 1607338689:0;cd prile/batch_processing/worker/commands/k8s
: 1607338879:0;git s
: 1607339157:0;cd prile/batch_processing/worker/commands/k8s
: 1607339300:0;git a .
: 1607339312:0;git cm "config argo attribution"
: 1607339313:0;git s
: 1607339319:0;git push origin staging
: 1607339687:0;git s
: 1607339689:0;git a .
: 1607339693:0;git cm "config argo attribution"
: 1607339701:0;git push origin staging
: 1607339794:0;git s
: 1607340247:0;cd prile/batch_processing/worker/commands/k8s
: 1607340295:0;cd prile/batch_processing/pipelines/commands/k8s
: 1607340386:0;git s
: 1607340832:0;cd ..
: 1607340840:0;ls -la
: 1607340894:0;ls
: 1607340932:0;clear
: 1607393450:0;		docker-compose up -d
: 1607393458:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607393471:0;cd prile/batch_processing/pipelines/commands/k8s
: 1607394750:0;kubectl get po | grep faust
: 1607394759:0;kubectl logs -f stag-faust-profile-update-75445cfdc8-kxzw2
: 1607394764:0;kubectl logs -f stag-faust-profile-update-7987465d86-gdvgl
: 1607395020:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607395115:0;git s
: 1607395139:0;git cm "removed hard code segment rfm metrics"
: 1607395140:0;git s
: 1607395146:0;git push origin staging
: 1607395805:0;k get ns
: 1607395811:0;kubectl get ns
: 1607395819:0;kubectl get pods
: 1607396069:0;git s
: 1607396074:0;git a .
: 1607396099:0;git cm "removed hard code segment rfm metrics"
: 1607396100:0;git s
: 1607396103:0;git push origin staging
: 1607402117:0;python3 --hellp
: 1607402119:0;python3 --help
: 1607402129:0;python3 --help | grep -m
: 1607402137:0;python3 --help | grep '-m'
: 1607402141:0;python3 --help
: 1607402215:0;python3 -m prile.batch_processing.rfm.rfm_updates
: 1607402253:0;python3 -m prile.batch_processing.pipelines.rfm.rfm_updates
: 1607402279:0;export | grep CONF
: 1607403438:0;python3 -m prile.batch_processing.pipelines.rfm.rfm_updates
: 1607407445:0;python3 -m prile.batch_processing.pipelines.rfm
: 1607407642:0;git s
: 1607407646:0;git a .
: 1607408713:0;git s
: 1607408718:0;git a .
: 1607408739:0;git cm "refactor rfm pipilines"
: 1607408740:0;git s
: 1607408744:0;git push origin staging
: 1607410097:0;which pycharm-professional
: 1607410113:0;which python
: 1607410156:0;pip3 install xlrd
: 1607410227:0;which jupyter
: 1607410236:0;conda install xlrd
: 1607410270:0;conda install xlrd >=1.0.0
: 1607410318:0;conda install -c anaconda xlrd
: 1607410419:0;pip install xlrd
: 1607416195:0;git a .
: 1607416235:0;git cm "rfm process refine cut off method"
: 1607416235:0;git s
: 1607416238:0;git push origin staging
: 1607416251:0;git s
: 1607417511:0;git a .
: 1607417544:0;git cm "split internal apis"
: 1607417545:0;git s
: 1607417549:0;git push origin staging
: 1607423305:0;git co staging
: 1607423306:0;git s
: 1607423431:0;git stash pop
: 1607426068:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607479744:0;		docker-compose up -d
: 1607479750:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607480616:0;git s
: 1607480633:0;git a .
: 1607480677:0;git cm "refactor get profile ptraits"
: 1607480677:0;git s
: 1607480682:0;git push origin staging
: 1607480741:0;git pull origin staging
: 1607480767:0;git s
: 1607480772:0;git push origin staging
: 1607480779:0;git s
: 1607480833:0;git co master
: 1607480842:0;git merge origin staging
: 1607480866:0;git push origin staging
: 1607480873:0;git push origin master
: 1607480953:0;git co staging
: 1607480958:0;cd prile/batch_processing/pipelines/commands/k8s
: 1607481535:0;git s
: 1607481879:0;cd prile/batch_processing/pipelines/commands/k8s
: 1607481916:0;cd prile/batch_processing/orchestration/commands/k8s
: 1607482157:0;git a .
: 1607482167:0;git cm "edited config argo"
: 1607482173:0;git push origin staging
: 1607484899:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607485495:0;history
: 1607485502:0;clera
: 1607485503:0;clear
: 1607485551:0;ssh 1.110.1.5
: 1607485590:0;git a .
: 1607485592:0;git s
: 1607485602:0;git cm "update sql"
: 1607485606:0;git push origin master
: 1607485684:0;./kafka-console-consumer.sh --bootstrap-server  \BC10.110.1.5:9092,10.110.1.5:9093,10.110.1.5:9094 \BD --topic profile-updated --from-beginning
: 1607485709:0;ssh root@1.110.1.5
: 1607485797:0;ssh root@10.110.1.5
: 1607489733:0;sudo apt-get install parcellite
: 1607489741:0;ls
: 1607489781:0;[200~    SELECT uniqMerge(value) AS total_user
: 1607489781:0;2020-12-09 11:23:47,931 INFO sqlalchemy.engine.base.Engine {'tenant_id': 1, 'source_scope': 'ADR-1htXpdVcfiprEmhWgs3GSEd13qF'}
: 1607489791:0;ADR-1htXpdVcfipr
: 1607496501:0;parcellite
: 1607496523:0;asdf asdfdsf parcellite
: 1607574154:0;		docker-compose up -d
: 1607574160:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607574416:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607574626:0;git a .
: 1607574627:0;git s
: 1607574634:0;git a .
: 1607574655:0;git cm "fix anonymous empty segment"
: 1607574656:0;git s
: 1607574660:0;git push origin staging
: 1607589357:0;	ssh root@10.110.1.5
: 1607589375:0;ssh root@103.57.210.44
: 1607650757:0;git s
: 1607650761:0;		docker-compose up -d
: 1607650768:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607654585:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607654836:0;export 
: 1607654841:0;export | grep CONFI
: 1607655438:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607673062:0;git a .
: 1607673097:0;git cm "add funnel function"
: 1607673098:0;git s
: 1607673103:0;git push origin master
: 1607673136:0;git s
: 1607678266:0;python3 -m prile.batch_processing.pipelines.fake_data_events
: 1607678656:0;ssh root@103.57.210.44
: 1607679188:0;clear
: 1607686434:0;git clone git@github.com:PostHog/posthog.git
: 1607687111:0;ls
: 1607687112:0;clear
: 1607687112:0;ls
: 1607687174:0;scp -i ~/.ssh/id_rsa fake_journey.py root@103.57.210.44:~
: 1607687466:0;scp -i ~/.ssh/id_rsa studio_mock_users root@103.57.210.44:~
: 1607687488:0;scp -i ~/.ssh/id_rsa studio_mock_users_2 root@103.57.210.44:~
: 1607687508:0;scp -i ~/.ssh/id_rsa studio_mock_users_2.csv root@103.57.210.44:~
: 1607687520:0;scp -i ~/.ssh/id_rsa studio_mock_users.csv root@103.57.210.44:~
: 1607737928:0;		docker-compose up -d
: 1607737939:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607912018:0;git s
: 1607912043:0;		docker-compose up -d
: 1607912047:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1607912071:0;git s
: 1607912475:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607912804:0;python3 -m prile.batch_processing.pipelines.fake_data_events
: 1607912891:0;git s
: 1607912894:0;git tree
: 1607913190:0;python3 -m prile.batch_processing.pipelines.fake_data_events
: 1607913222:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607913919:0;git s
: 1607913950:0;git cm 'remove hardcode'
: 1607913951:0;git 
: 1607913952:0;git s
: 1607913954:0;git a .
: 1607913956:0;git cm 'remove hardcode'
: 1607913957:0;git s
: 1607913962:0;git push origin staging
: 1607914014:0;git
: 1607914015:0;git s
: 1607914016:0;git tree
: 1607914027:0;git push origin staging
: 1607914126:0;git pull origin staging
: 1607914373:0;git s
: 1607914395:0;git checkout master
: 1607914396:0;git s
: 1607914401:0;git merge origin staging
: 1607914408:0;git tree
: 1607914414:0;git push origin master
: 1607914424:0;git tree
: 1607914437:0;git checkout staging
: 1607914442:0;git push origin staging
: 1607915985:0;git clone https://github.com/PostHog/posthog-python.git
: 1607916150:0;pip install posthog
: 1607916283:0;which python
: 1607916360:0;git s
: 1607916365:0;cd ..
: 1607916366:0;ls
: 1607916368:0;cd PYTHON
: 1607916369:0;ls
: 1607916370:0;cd generator
: 1607916371:0;ls
: 1607916373:0;clear
: 1607916377:0;which python3
: 1607916386:0;which python
: 1607916461:0;cd ..
: 1607916464:0;cd clickhouse
: 1607916469:0;which pip3
: 1607916477:0;which pip
: 1607916484:0;pip install posthog
: 1607916496:0;clear
: 1607916984:0;which python
: 1607917089:0;which python3
: 1607917096:0;pip install .
: 1607917103:0;which pip3
: 1607932147:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1607940971:0;git clone https://github.com/Hungsiro506/Demo-MovieLens.git
: 1607999491:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608023123:0;		docker-compose up -d
: 1608023126:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608083542:0;		docker-compose up -d
: 1608083546:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608083554:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608084430:0;git s 
: 1608084443:0;git a .
: 1608084460:0;git cm "attribution dimension view api"
: 1608084461:0;git s
: 1608084505:0;git co -b ptrait_naming
: 1608084936:0;git a .
: 1608084969:0;git cm "rename fields for get ptrait api"
: 1608084971:0;git s 
: 1608084978:0;git s
: 1608084988:0;git push origin ptrait_naming
: 1608085020:0;git checkout staging
: 1608092867:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608115388:0;git a .
: 1608115492:0;git cm 'atrribution apis base'
: 1608115493:0;git s
: 1608115497:0;git push origin staging
: 1608170874:0;		docker-compose up -d
: 1608170879:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608170887:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608171210:0;git s
: 1608171555:0;git cm "attribution - rename function"
: 1608171557:0;git a .
: 1608171558:0;git cm "attribution - rename function"
: 1608171558:0;git s
: 1608171587:0;git merge origin ptrait_naming
: 1608171592:0;git s
: 1608171597:0;git push origin staging
: 1608171623:0;git pull origin staging
: 1608171635:0;git push origin staging
: 1608191525:0;git s
: 1608194303:0;git a .
: 1608194330:0;git cm "calculate attribution, interate with Vu"
: 1608194334:0;git push origin staging
: 1608194418:0;git pull origin staging
: 1608195587:0;python3 -m prile.analytics.attribution_version_just_touchpoint.process.on_the_fly
: 1608197800:0;git s
: 1608197830:0;git a .
: 1608197869:0;git cm "interate with Vu"
: 1608197869:0;git s
: 1608197875:0;git pull origin staging
: 1608197920:0;git a .
: 1608197921:0;git s
: 1608197934:0;git cm "Vu fix and merge"
: 1608197935:0;git s
: 1608199599:0;git a .
: 1608199613:0;git cm "fix api attribution"
: 1608199613:0;git s
: 1608199617:0;git push origin staging
: 1608200242:0;kubectl get po | grep fast
: 1608200260:0;git s
: 1608200333:0;git stash save
: 1608200345:0;git s
: 1608200349:0;git push origin staging
: 1608200478:0;git a .
: 1608200555:0;git cm "rename path name"
: 1608200556:0;git s
: 1608200559:0;git push origin staging
: 1608200568:0;git s
: 1608200570:0;git a .
: 1608200574:0;git cm 'rename path name'
: 1608200575:0;git s
: 1608200577:0;git push origin staging
: 1608202167:0;git stash save
: 1608202169:0;git s
: 1608203296:0;git stash pop
: 1608205976:0;git s 
: 1608205978:0;git a .
: 1608206000:0;git cm 'expose attribute campaign view'
: 1608206001:0;git s
: 1608206008:0;git pull origin staging
: 1608206017:0;git s
: 1608206098:0;python3 -v
: 1608206107:0;python3 --version
: 1608206142:0;git s
: 1608206165:0;clear
: 1608206469:0;git s
: 1608206478:0;git a .
: 1608206506:0;git cm "fix func ncr"
: 1608206507:0;git s
: 1608206511:0;git push origin staging
: 1608255945:0;git s
: 1608255982:0;		docker-compose up -d
: 1608255991:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608255999:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608256541:0;docekr ps
: 1608256543:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608256549:0;		docker-compose up -d
: 1608258050:0;git s
: 1608258054:0;git stash save
: 1608258055:0;git s
: 1608258530:0;git a .
: 1608258531:0;git s
: 1608258545:0;git cm "fill na value"
: 1608258545:0;git s
: 1608258552:0;git push origin staging
: 1608267064:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608267814:0;git s
: 1608267824:0;git a .
: 1608267851:0;git cm "attribution api not support pagination"
: 1608267852:0;git s
: 1608267857:0;git pull origin staging
: 1608267867:0;git s
: 1608268110:0;git a .
: 1608268125:0;git cm "support campaign grouping all traffic"
: 1608268126:0;git s
: 1608268129:0;git push origin staging
: 1608268206:0;clear
: 1608275265:0;git a .
: 1608275271:0;git cm "added dimension id"
: 1608275271:0;git s
: 1608275277:0;git push origin staging
: 1608275678:0;git git s
: 1608275679:0;git s
: 1608275728:0;git checkout fix_segment_sample_user
: 1608275744:0;git co -b fix_segment_sample_user
: 1608275745:0;git s
: 1608280247:0;git a .
: 1608280304:0;git s
: 1608280306:0;git a .
: 1608280529:0;git s
: 1608280544:0;git cm "refactor attribution: use config id"
: 1608280545:0;git s
: 1608280549:0;git co staging
: 1608280550:0;git s
: 1608280557:0;git merge refactor_attribution
: 1608280558:0;git s
: 1608280561:0;git push origin staging
: 1608281293:0;git s
: 1608282510:0;kubectl get po | grep faust
: 1608282520:0;kubectl get po | grep fast
: 1608282527:0;kubectl logs -f stag-fast-api-event-processing-545886f544-lsp5p
: 1608285180:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608286397:0;git s
: 1608286402:0;git a .
: 1608286411:0;git cm "hidden attribution model"
: 1608286412:0;git s
: 1608286416:0;git push origin staging
: 1608350656:0;git pull origin master
: 1608360466:0;		docker-compose up -d
: 1608360472:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608362629:0;which python3
: 1608362638:0;pip3 install .
: 1608362648:0;which pip3
: 1608362701:0;pip3 install requirements.txt
: 1608362824:0;pip3 install -r requirements-dev.txt
: 1608362958:0;pip3 install .
: 1608362972:0;pip3 install -r requirements.txt
: 1608363176:0;which python3
: 1608363180:0;python3 -v
: 1608363188:0;python3 -version
: 1608363194:0;python3 --version
: 1608363251:0;conda install -c anaconda python=3.8
: 1608364993:0;git s
: 1608365039:0;git co master
: 1608365043:0;git merge staging
: 1608365053:0;git push origin master
: 1608365073:0;git s
: 1608365991:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1608366939:0;git s
: 1608367054:0;git stash save
: 1608367054:0;git s
: 1608367065:0;git co staging
: 1608367066:0;git s
: 1608367070:0;git stash save
: 1608367071:0;git s
: 1608367076:0;git stash pop
: 1608367078:0;git s
: 1608367081:0;git a .
: 1608367100:0;git cm 'fix get sample user by segment'
: 1608367101:0;git s
: 1608367106:0;git push origin staging
: 1608367877:0;git checkout master
: 1608367882:0;git merge staging
: 1608367887:0;git push origin master
: 1608519656:0;		docker-compose up -d
: 1608519661:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608519669:0;1
: 1608519693:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608519749:0;cd /home/chile/Downloads
: 1608519749:0;ls
: 1608519757:0;ls -la
: 1608519901:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608519930:0;cd ..
: 1608519932:0;cd Documents
: 1608519932:0;ls
: 1608519936:0;cd pem
: 1608519938:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608520346:0;		docker-compose up -d
: 1608520352:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608520992:0;cd ee
: 1608521144:0;		docker-compose up -d
: 1608523727:0;		docker-compose -f docker-compose.ch.yml up -d
: 1608525651:0;docker stop $(docker ps -aq)
: 1608525669:0;		docker-compose -f docker-compose.ch.yml up -d
: 1608525679:0;clear
: 1608525681:0;		docker-compose -f docker-compose.ch.yml up -d
: 1608527024:0;docker ps
: 1608538865:0;docker 
: 1608538868:0;docker ps
: 1608539155:0;docker exec -it 030e7e01db81 /bin/bash
: 1608539535:0;clear
: 1608539586:0;docker ps
: 1608539611:0;docker exec -it 030e7e01db81 /bin/bash
: 1608539838:0;./kafka-console-consumer.sh --bootstrap-server "localhost:9092" --topic clickhouse_person --from-beginning
: 1608539857:0;docker exec -it 030e7e01db81 /bin/bash
: 1608550652:0;source activate
: 1608550672:0;python --version
: 1608550684:0;pip install -r requirements.txt
: 1608550698:0;ls
: 1608550699:0;clear
: 1608550708:0;export DEBUG=1
: 1608550713:0;export PRIMARY_DB=clickhouse
: 1608550721:0;export DATABASE_URL=postgres://posthog:posthog@localhost:5439/posthog
: 1608550871:0;docker stop $(docker ps -aq)
: 1608550906:0;docker-compose -f ee/docker-compose.ch.yml up db redis zookeeper kafka clickhouse
: 1608550923:0;vi /etc/hosts
: 1608550937:0;sudo vi /etc/hosts
: 1608551005:0;sudo nano /etc/hosts
: 1608551042:0;python manage.py migrate && python manage.py migrate_clickhouse
: 1608551766:0;yarn -v
: 1608551779:0;yarn build
: 1608551820:0;yarn upgrade
: 1608551872:0;yarn build
: 1608551945:0;sudo apt update
: 1608551959:0;sudo apt install build-essential checkinstall libssl-dev
: 1608551968:0;curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.35.1/install.sh | bash
: 1608551995:0;nvm --version
: 1608552033:0;curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.35.1/install.sh | bash
: 1608552057:0;export NVM_DIR="$HOME/.nvm"\
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm\
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion\

: 1608552069:0;nvm --version
: 1608552075:0;nvm ls
: 1608552090:0;nvm ls-remote
: 1608552120:0;nvm install v14.15.3
: 1608552131:0;node -v
: 1608552145:0;yarn build
: 1608552165:0;node -v
: 1608552188:0;nvm ls
: 1608552247:0;nvm install
: 1608552289:0;nvm --version
: 1608552298:0;which user
: 1608552303:0;which nvm
: 1608552322:0;npm cache clean -f
: 1608552332:0;npm install -g n
: 1608552341:0;dudo npm install -g n
: 1608552345:0;sudo npm install -g n
: 1608552364:0;npm install -g n
: 1608552368:0;sudo npm install -g n
: 1608552517:0;git clone git@github.com:primedata-ai/pposthog.git
: 1608552702:0;python --version
: 1608566301:0;conda install -c anaconda python=3.8
: 1608566479:0;which python3
: 1608566538:0;git clone git@github.com:primedata-ai/pposthog.git
: 1608566675:0;source activate
: 1608566716:0;pip3 install -r requirements.txt
: 1608566868:0;git pull origin master
: 1608566876:0;git pull origin develop
: 1608567010:0;python3 --version
: 1608567023:0;sudo apt update -y
: 1608567050:0;sudo apt install python3.8
: 1608567079:0;sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 1
: 1608567086:0;sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.8 2
: 1608567136:0;sudo rm /usr/bin/python3
: 1608567142:0;sudo ln -s python3.8 /usr/bin/python3
: 1608567148:0;python3 -V
: 1608567158:0;sudo update-alternatives --config python3
: 1608567194:0;python3
: 1608567205:0;python3.8 -V
: 1608567215:0;which python3.8
: 1608567361:0;python3
: 1608567387:0;source activate
: 1608567396:0;which python
: 1608567400:0;python -V
: 1608567412:0;pip3 install -r requirements.txt
: 1608567426:0;which pip3
: 1608567449:0;pip install -r requirements.txt
: 1608567583:0;cd ee
: 1608567605:0;docker-compose -f docker-compose.prime.yml up 
: 1608567623:0;cd .python/bin
: 1608567632:0;source active
: 1608567636:0;source activate
: 1608567640:0;cd ..
: 1608567647:0;cd ee
: 1608567675:0;cd bin
: 1608567683:0;./prime-start-worker
: 1608567739:0;pip list
: 1608567759:0;./prime-start-worker
: 1608567787:0;which celery
: 1608567819:0;cd ..
: 1608567841:0;ee/bin/prime-start-worker
: 1608568036:0;docker-compose -f docker-compose.prime.yml up 
: 1608568159:0;docker stop $(docker ps -aq)
: 1608568175:0;docker-compose -f docker-compose.prime.yml up 
: 1608568191:0;docker ps
: 1608568217:0;ee/bin/prime-start-worker
: 1608568343:0;docker ps  -a
: 1608568368:0;docker ps
: 1608568595:0;docker ls -la
: 1608568597:0;docker ls -a
: 1608568602:0;docker ps -la
: 1608568609:0;docker ps -a
: 1608568651:0;docker volume ps 
: 1608568656:0;docker volume ls
: 1608568662:0;docker volume -h
: 1608568678:0;docker volume rm $(docker volume ls -a -q)
: 1608568684:0;docker volume rm $(docker volume ls )
: 1608568691:0;docker volume ls
: 1608568720:0;docker volume rm posthog_postgres-data
: 1608568732:0;docker stop $(docker ps -aq)
: 1608568748:0;docker volume ls
: 1608568756:0;docker volumn rm posthog_postgres-data
: 1608568766:0;docker volume ls
: 1608568771:0;docker volume rm posthog_postgres-data
: 1608568788:0;docker volume -h
: 1608568798:0;docker volume prune
: 1608568803:0;docker volume ls
: 1608568817:0;docker volume rm posthog_postgres-data
: 1608568822:0;docker ps
: 1608568826:0;docker ps -a
: 1608568886:0;docker rm $(docker ps -a -f status=exited -q)
: 1608568889:0;docker ps -a
: 1608568896:0;docker ps
: 1608568901:0;docker containers
: 1608568904:0;docker container
: 1608568908:0;docker container ls
: 1608568912:0;docker container ls -a
: 1608568936:0;docker rm $(docker ps -a -f status=exited -q)
: 1608568943:0;docker container rm 
: 1608568946:0;docker container rm -h
: 1608568958:0;docker container rm aec8daaefe7c
: 1608568963:0;docker container ls
: 1608568966:0;docker container ls -a
: 1608568988:0;docker container rm c7d8fcf264c5
: 1608568995:0;docker container rm e0555163f05a
: 1608568998:0;docker container ls
: 1608569002:0;docker container ls -a
: 1608569023:0;docker container rm 39e940ace35a e12f03f1e3b0
: 1608569029:0;docker-compose -f docker-compose.prime.yml up 
: 1608569053:0;clear
: 1608569054:0;docker-compose -f docker-compose.prime.yml up 
: 1608569079:0;ee/bin/prime-start-worker
: 1608569175:0;docker ps
: 1608569490:0;docker-compose -f docker-compose.prime.yml up -d
: 1608569500:0;docker-compose -f docker-compose.prime.yml logs -f frontend
: 1608569732:0;docker ps
: 1608570556:0;docker-compose -f docker-compose.prime.yml logs -f frontend
: 1608570571:0;ee/bin/prime-start-worker
: 1608570692:0;docker-compose -f docker-compose.prime.yml down
: 1608570718:0;docker-compose -f docker-compose.prime.yml up
: 1608571606:0;clear
: 1608571608:0;docker ps
: 1608596297:0;which python3
: 1608596307:0;pip install Faker
: 1608596400:0;which pip3
: 1608596465:0;which python3
: 1608596475:0;pip install Faker
: 1608596926:0;faker -h
: 1608600287:0;docker-compose -f docker-compose.prime.yml up
: 1608600298:0;history
: 1608600307:0;history | grep docker-compose
: 1608600344:0;ee/bin/prime-start-worker
: 1608603911:0;ifconfig
: 1608603977:0;ipconfig
: 1608603979:0;ifconfig
: 1608604094:0;curl ifconfig.me
: 1608604422:0;ifconfig -a
: 1608604457:0;ifconfig -a | grep 192.
: 1608614060:0;ee/bin/prime-start-worker
: 1608614722:0;docker ps
: 1608614778:0;ee/bin/prime-start-worker
: 1608686966:0;docker-compose -f docker-compose.prime.yml up
: 1608686988:0;git pull origin develop
: 1608687000:0;git s
: 1608687013:0;git stash save 'fix front end'
: 1608687014:0;git s
: 1608687024:0;git pull origin develop
: 1608687030:0;git 
: 1608687031:0;git s
: 1608687100:0;pip install -r requirements.txt
: 1608687145:0;docker-compose -f docker-compose.prime.yml up
: 1608687148:0;docker-compose -f ee/docker-compose.prime.yml up
: 1608687169:0;ee/bin/prime-start-worker
: 1608688973:0;telnet 103.57.210.44
: 1608689181:0;git pull origin develop
: 1608689683:0;git tree
: 1608689708:0;docker stop $(docker ps -aq)
: 1608689714:0;docker ps
: 1608689731:0;docker rm -h
: 1608689749:0;docker ps -a
: 1608689792:0;docker rm 98d9704a59e3 36d1d62755ef 16057debcb0e e759adaf7da7 176c89c4af05 cb0015ec9bf6
: 1608689797:0;docker ps -a
: 1608689802:0;git pull origin develop
: 1608689862:0;ifconfig
: 1608689986:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608690336:0;docker ps
: 1608690891:0;netstat -tlpn
: 1608691631:0;git pull origin develop
: 1608691640:0;git s
: 1608699245:0;git stash save
: 1608699246:0;git s
: 1608699251:0;git pull origin develop
: 1608699418:0;git s
: 1608699423:0;git pull origin develop
: 1608699460:0;git s
: 1608699734:0;git pull origin develop
: 1608700194:0;git s
: 1608700510:0;faker -v
: 1608711997:0;git pull origin develop
: 1608715541:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608719627:0;ssh 103.57.210.44
: 1608719669:0;ssh root@103.57.210.44
: 1608719744:0;ssh root@103.57.210.44:22
: 1608719747:0;ssh root@103.57.210.44 22
: 1608719759:0;ssh root@103.57.210.44
: 1608721375:0;git clone git@github.com:primedata-ai/posthog-python.git
: 1608721689:0;source .python/bin/activate
: 1608721705:0;pip install prime/generator/requirements.txt
: 1608721713:0;pip install -r prime/generator/requirements.txt
: 1608721726:0;ls cpu
: 1608721729:0;lscpu
: 1608721875:0;python3 -m prime.generator.gen_data --id-start 1000001 --id-end 1500000 --threads 2
: 1608721978:0;clear
: 1608721995:0;ls
: 1608721995:0;clear
: 1608722184:0;git pull origin
: 1608722195:0;git s
: 1608722216:0;git a .
: 1608722223:0;git cm 'fix path'
: 1608722225:0;git s
: 1608722228:0;git pull origin
: 1608722247:0;python3 -m prime.generator.gen_data --id-start 1000001 --id-end 1500000 --threads 2
: 1608722457:0;git s 
: 1608722466:0;git cm 'fix tuple chunk'
: 1608722466:0;git 
: 1608722468:0;git s
: 1608722472:0;git push origin
: 1608722482:0;git pull 
: 1608722489:0;git s
: 1608722491:0;git a .
: 1608722496:0;git cm 'fix tuple chunk'
: 1608722497:0;git s
: 1608722500:0;git push origin
: 1608722506:0;git pull
: 1608722529:0;git a .
: 1608722533:0;git cm "merged"
: 1608722534:0;git s
: 1608722540:0;git push origin
: 1608722564:0;git tree
: 1608723116:0;git s
: 1608723118:0;git a .
: 1608723125:0;git cm 'fix chunk tuple'
: 1608723126:0;git s
: 1608723130:0;git push origin
: 1608723180:0;git s
: 1608725188:0;python3 -m prime.generator.gen_data --id-start 1000001 --id-end 1500000 --threads 2
: 1608774543:0;git pull origin develop
: 1608774745:0;git s
: 1608774766:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608774823:0;ifconfig
: 1608775240:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608775302:0;git pull origin develop
: 1608775512:0;docker stop $(docker ps -aq)
: 1608775518:0;docker ps -l
: 1608775525:0;docker container ls
: 1608775529:0;docker ps -a
: 1608775553:0;docker rm d55c749e4723 2a81e8aeba0c 7545074f00ea 82c789b3dba7 8eab837b8d6b 3f0dee7203fd
: 1608775556:0;docker ps -a
: 1608775561:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608775940:0;python3 -m prime.generator.gen_data --id-start 1000001 --id-end 1500000 --threads 2
: 1608775979:0;git s
: 1608775982:0;git tree
: 1608776016:0;git s
: 1608776764:0;docker stop $(docker ps -aq)
: 1608776771:0;docker ps -a
: 1608776782:0;docker rm  $(docker ps -aq)
: 1608776788:0;docker ps -a
: 1608776994:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608777232:0;python3 -m prime.generator.gen_data --id-start 1000001 --id-end 1500000 --threads 2
: 1608777629:0;docker-compose -f ee/docker-compose.prime.yml down
: 1608777965:0;cd prime
: 1608777983:0;docker-compose -f docker-compose.prime.yml down
: 1608778010:0;docker-compose -f docker-compose.prime.yml up
: 1608778107:0;python3 -m prime.generator.gen_data --id-start 1000001 --id-end 1500000 --threads 2
: 1608778156:0;git pull origin
: 1608778165:0;git s
: 1608778167:0;git a .
: 1608778168:0;git s
: 1608778225:0;which python
: 1608778360:0;source .python/bin/avtivate
: 1608778370:0;source .python/bin/activate
: 1608778374:0;which python
: 1608778382:0;pip install -r prime/generator/requirements.txt
: 1608778465:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 2
: 1608778595:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 1
: 1608778849:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 2
: 1608780009:0;docker-compose -f docker-compose.prime.yml --build up 
: 1608780021:0;docker-compose -f docker-compose.prime.yml  up --build 
: 1608780855:0;ifconfig
: 1608780921:0;docker-compose -f docker-compose.prime.yml  up --build 
: 1608781115:0;git s
: 1608781170:0;docker ps
: 1608781174:0;git s
: 1608781184:0;docker-compose -f docker-compose.prime.yml  up --build 
: 1608781224:0;git s
: 1608781291:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1608781595:0;git s
: 1608781643:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1608781733:0;docker ps
: 1608781819:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 2
: 1608783395:0;ssh @103.57.210.44:8000
: 1608783402:0;ssh root@103.57.210.44:8000
: 1608783414:0;ssh root@103.57.210.44
: 1608783663:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 2
: 1608783834:0;docker-compose -f ./prime/docker-compose.prime.yml up --build
: 1608784210:0;htop
: 1608784247:0;sudo apt install htop
: 1608784267:0;htop
: 1608784651:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM 
: 1608784810:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server 103.57.210.44:8000
: 1608784818:0;git s
: 1608784843:0;git a .
: 1608784989:0;python3 -m prime.generator.gen_data --id-start 0 --id-end 1500000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server 103.57.210.44:8000
: 1608784997:0;git a .
: 1608785006:0;git cm 'added api key, server '
: 1608785007:0;git s
: 1608785024:0;git pull origin
: 1608785031:0;git tree
: 1608785091:0;git s
: 1608785095:0;git pull origin
: 1608785111:0;git cm 'added api key, server '
: 1608785114:0;git push origin
: 1608785125:0;git s
: 1608785294:0;git a .
: 1608785297:0;git s
: 1608785539:0;python3 -m prime.generator.gen_data --id-start 1000001 --id-end 1500000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server 103.57.210.44
: 1608785993:0;git a .
: 1608785998:0;git cm 'fix name'
: 1608785998:0;git s
: 1608786001:0;git push origin
: 1608786022:0;git s
: 1608786279:0;python3 -m prime.generator.gen_data --id-start 2000001 --id-end 2200000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server 103.57.210.44
: 1608786524:0;git pull origin
: 1608786534:0;python3 -m prime.generator.gen_data --id-start 2000001 --id-end 2200000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server 103.57.210.44
: 1608797098:0;git s
: 1608797162:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1608802676:0;git s
: 1608802684:0;clear
: 1608802837:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608803065:0;ssh -L 9092:127.0.0.1:9092 root@103.57.210.44
: 1608810677:0;git pull origin
: 1608810831:0;python3 -m prime.generator.gen_data --id-start 2000001 --id-end 2200000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server 103.57.210.44
: 1608810869:0;python3 -m prime.generator.gen_data --id-start 4000001 --id-end 4200000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server 103.57.210.44
: 1608857175:0;git pull origin
: 1608857840:0;python3 -m prime.generator.gen_data --id-start 4000001 --id-end 4200000 --threads 2 --api-key XcBWuVrgEXXN2E4oi91x3BnkIWxJlaT6dl6mdCuCFvM --api-server localhost
: 1608857867:0;python3 -m prime.generator.gen_data --id-start 4000001 --id-end 4200000 --threads 2 --api-key EWoV4tiiP8hOb-zdlilGmQ2BFTGW0kAyxMiwMyfxixU --api-server localhost
: 1608867635:0;git s
: 1608870713:0;pip install faust
: 1608874269:0;git pull origin
: 1608875499:0;pip install faust
: 1608883409:0;faust -A prime.transform.app pipelines -l info -p 6067
: 1608883488:0;faust -A prile.workflows.events_campaign.app worker -l info -p 6066
: 1608883508:0;faust -A prime.transform.app pipelines -l info -p 6067
: 1608883525:0;faust -A prime.transform.app worker -l info -p 6067
: 1608884665:0;pip install snappy
: 1608884842:0;pip install python-snappy
: 1608884958:0;python --version
: 1608885109:0;deactivate
: 1608885121:0;/usr/bin/python3
: 1608885130:0;sudo apt-get install python3-dev -y
: 1608885199:0;pip install python-snappy
: 1608885285:0;python --version
: 1608885331:0;sudo apt-get install python3.8-dev
: 1608885363:0;pip install python-snappy
: 1608885445:0;faust -A prime.transform.app worker -l info -p 6067
: 1608885482:0;pip LIST
: 1608885485:0;pip list
: 1608885502:0;python
: 1608885553:0;which python
: 1608885561:0;faust -A prime.transform.app worker -l info -p 6067
: 1608885681:0;pip install loguru
: 1608885757:0;faust -A prime.transform.app worker -l info -p 6067
: 1608887780:0;pip list
: 1608887833:0;pip install -r prime/transform/requirements.txt
: 1608887955:0;pip list
: 1608888218:0;kubectl port-forward svc/consul-ui 8501:80
: 1608888330:0;docker-compose -f  docker-compose.yml up consul-server-bootstrap
: 1608888340:0;kubectl port-forward svc/consul-ui 8501:80
: 1608889680:0;faust -h
: 1608889687:0;faust --help
: 1608889694:0;faust worker --help
: 1608890256:0;docker-compose -f docker-compose.tf.yml up -d worker
: 1608890278:0;kubectl port-forward svc/consul-ui 8501:80
: 1608890332:0;docker image ls
: 1608890347:0;docker run -it python:3.8-slim bash
: 1608890874:0;faust -A prime.transform.app worker -l info -p 6067
: 1608891289:0;git s
: 1608891319:0;git status
: 1608891387:0;git add .
: 1608891429:0;rm -f .python
: 1608891434:0;rm -rf .python
: 1608891436:0;ls
: 1608891438:0;ls -la
: 1608891456:0;git s
: 1608891463:0;git a .
: 1608891475:0;git cm 'posthog transorm event workers'
: 1608891476:0;git s
: 1608891686:0;source .python/bin/activate
: 1608891690:0;which python
: 1608891710:0;pip install -r requirements.txt
: 1608891731:0;git s
: 1608891746:0;faust -A prime.transform.app worker -l info -p 6067
: 1608891787:0;which pythob
: 1608891791:0;which python
: 1608891794:0;faust -A prime.transform.app worker -l info -p 6067
: 1608892100:0;which faust
: 1608892164:0;/home/chile/PycharmProjects/Github/PrimeData/posthog-python/.python/bin/faust
: 1608893733:0;ls
: 1608893734:0;clear
: 1608893755:0;rm -rf .python
: 1608893756:0;ls
: 1608893860:0;source .python/bin/activate
: 1608893864:0;which python
: 1608893866:0;ls
: 1608893868:0;clear
: 1608893930:0;faust -A prime.transform.app worker -l info -p 6067
: 1608893939:0;pip list
: 1608893958:0;pip install faust
: 1608893972:0;pip install faust python-snappy python-consul
: 1608893981:0;pip install faust python-snappy python-consul PyYAML
: 1608894096:0;faust -A prime.transform.app worker -l info -p 6067
: 1608894115:0;pip install pyconsul
: 1608894183:0;faust -A prime.transform.app worker -l info -p 6067
: 1608894204:0;pip list
: 1608894208:0;pip list | consul
: 1608894214:0;pip list | grep consul
: 1608894220:0;faust -A prime.transform.app worker -l info -p 6067
: 1608894228:0;python
: 1608894240:0;faust -A prime.transform.app worker -l info -p 6067
: 1608894654:0;python
: 1608894833:0;pip install requirements.txt
: 1608894838:0;pip install -r requirements.txt
: 1608894967:0;faust -A prime.transform.app worker -l info -p 6067
: 1608894982:0;python 
: 1608894999:0;faust -A prime.transform.app worker -l info -p 6067
: 1608895048:0;python 
: 1608895067:0;faust -A prime.transform.app worker -l info -p 6067
: 1608895119:0;python setup.py
: 1608895132:0;python setup.py --help
: 1608895152:0;python setup.py install 
: 1608895165:0;faust -A prime.transform.app worker -l info -p 6067
: 1608901120:0;history
: 1608901302:0;faust -A prime.transform.app worker -l info -p 6067
: 1608901465:0;git s
: 1608901477:0;git a .
: 1608901500:0;git cm "added env"
: 1608901501:0;git s
: 1608901503:0;git push origin
: 1608901587:0;git a .
: 1608901593:0;git cm "removed log"
: 1608901594:0;git s
: 1608901597:0;git push origin
: 1608906064:0;git s 
: 1608906087:0;git diff
: 1608906223:0;git pull origin
: 1608906302:0;git s
: 1608906318:0;git cm 'updated schema api'
: 1608906319:0;git s
: 1608906419:0;git add . 
: 1608906460:0;git commit -m "[master] update schema api" --no-verify
: 1608906483:0;git rm .python 
: 1608906489:0;git rm -r .python 
: 1608906545:0;git s
: 1608906561:0;git cm -m 'remove env'
: 1608906779:0;source venv/bin/activate
: 1608906798:0;pip install -r requirements.txt
: 1608906831:0;git s
: 1608906847:0;git a .
: 1608906848:0;git s
: 1608906856:0;git cm 'deleted env'
: 1608906866:0;git cm 'deleted env' --no-verify
: 1608906870:0;git s
: 1608907644:0;faust -A prime.transform.app worker -l info -p 6067
: 1608908073:0;source venv/bin/activate
: 1608908087:0;pip list
: 1608908108:0;pip install -r requirements.txt
: 1608908250:0;faust -A prime.transform.app worker -l info -p 6067
: 1608908311:0;git s
: 1608908314:0;git a .
: 1608908325:0;git cm 'update team id'
: 1608908328:0;git push origin
: 1608908346:0;git s
: 1608909617:0;docker ps
: 1608909636:0;docker-compose -f prime/docker-compose.prime.yml down
: 1608909662:0;docker ps -a
: 1608909672:0;docker ps -la
: 1608909675:0;docker ps -a
: 1608909687:0;docker-compose -f prime/docker-compose.prime.yml up bild
: 1608909690:0;docker-compose -f prime/docker-compose.prime.yml up build
: 1608909695:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1608909773:0;faust -A prime.transform.app worker -l info -p 6067
: 1608910193:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1608910420:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608910874:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1608911085:0;clear
: 1608911086:0;docker ps
: 1608911124:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608911216:0;faust -A prime.transform.app worker -l info -p 6067
: 1608911505:0;git s
: 1608911513:0;git cm "rename app name"
: 1608911514:0;git s
: 1608911515:0;git a .
: 1608911517:0;git cm "rename app name"
: 1608911520:0;git push origin
: 1608911532:0;git s
: 1608911535:0;git a .
: 1608911549:0;git cm "optimized session query"
: 1608911557:0;git cm "optimized session query" --no-verify
: 1608911559:0;git s
: 1608911562:0;git pull origin
: 1608911571:0;git push origin
: 1608911833:0;faust -A prime.transform.app worker -l info -p 6067
: 1608911862:0;faust -A prime.transform.app worker -l info -p 6068j
: 1608911864:0;faust -A prime.transform.app worker -l info -p 6068
: 1608914981:0;git s
: 1608915001:0;git a .
: 1608915013:0;git cm "rename session id event"
: 1608915014:0;git s
: 1608915018:0;git push origin
: 1608915107:0;git s
: 1608915125:0;git co -b session
: 1608915126:0;git s
: 1608915128:0;git a .
: 1608915138:0;git cm "refactor session sql"
: 1608915139:0;git s
: 1608915146:0;git cm "refactor session sql" --no-verify
: 1608915147:0;git s
: 1608915151:0;git push origin session
: 1608915582:0;git 
: 1608915594:0;git s
: 1608916121:0;git tree
: 1608916709:0;git checkout develop
: 1608916744:0;git merge session
: 1608916745:0;git s
: 1608916749:0;git push origin develop
: 1608916757:0;git pull origin
: 1608916769:0;git push origin
: 1608917663:0;pip list | grep consul
: 1608917673:0;kubectl port-forward svc/consul-ui 8501:80
: 1608918244:0;git pull origin
: 1608918317:0;clear
: 1608918318:0;git s
: 1608918320:0;clear
: 1608970577:0;git show origin
: 1608970763:0;docker run -it python3.8-slim bash
: 1608970770:0;docker run -it python:3.8-slim bash
: 1608971476:0;kubectl port-forward svc/consul-ui 8501:80
: 1608971734:0;docker-compose -f prime/docker-compose.prime.yml up
: 1608971765:0;docker-compose -f docker-compose.yml up
: 1608971775:0;kubectl port-forward svc/consul-ui 8501:80
: 1608971783:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608971789:0;docker ps
: 1608971793:0;kubectl port-forward svc/consul-ui 8501:80
: 1608972046:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608972071:0;cd ~/Downloads
: 1608972071:0;ls
: 1608972118:0;cd ..
: 1608972120:0;cd Documents
: 1608972123:0;cd pem
: 1608972125:0;sudo openvpn --config chile-118.68.168.185.ovpn
: 1608972134:0;kubectl port-forward svc/consul-ui 8501:80
: 1608972269:0;docker ps
: 1608972276:0;kubectl get po 
: 1608972281:0;kubectl get po | grep faust
: 1608972298:0;kubectl logs -f stag-faust-pr2po-event-sync-64f477675f-qsvcc
: 1609121859:0;htop
: 1609122315:0;docker-compose -f docker-compose.yml up
: 1609122340:0;cd Documents
: 1609122353:0;cd ~/Documents
: 1609122356:0;ls
: 1609122358:0;cd pem
: 1609122377:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609122395:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609122428:0;docker ps
: 1609122473:0;docker-compose -f docker-compose.yml up --build
: 1609122499:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609122513:0;docker ps
: 1609122535:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609122577:0;docker ps -a
: 1609122584:0;docker stop $(docker ps -aq)
: 1609122588:0;docker ps -a
: 1609122606:0;docker rmi $(docker ps -aq)
: 1609122647:0;docker rm $(docker ps -aq)
: 1609122650:0;docker ps -a
: 1609122683:0;clear
: 1609122745:0;docker-compose -f docker-compose.yml up --build
: 1609122760:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609123004:0;kubectl get po | grep fast
: 1609123057:0;clear
: 1609123074:0;kubectl port-forward svc/consul-ui 8501:80
: 1609123127:0;clear
: 1609123137:0;kubectl port-forward svc/consul-ui 8501:80
: 1609123864:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609124838:0;export CONFIG_NAMESPACE
: 1609124847:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609124883:0;docker-compose -f docker-compose.yml up
: 1609124893:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609125163:0;export
: 1609125168:0;export | grep CONFI
: 1609125250:0;export CONFIG_NAMESPACE=prime/eventify/stag/event-processing-stag
: 1609126425:0;kubectl get po | grep 
: 1609126434:0;kubectl get po | grep fust
: 1609126437:0;kubectl get po | grep fast
: 1609126440:0;kubectl get po | grep faust
: 1609126486:0;kubectl logs -f faust-profile-update-75b4b94bf4-2fk2z
: 1609126562:0;kubectl get po | grep faust
: 1609126608:0;kubectl logs -f faust-pr2po-event-sync-d4d574d47-gg97n
: 1609126641:0;kubectl get po | grep faust
: 1609126649:0;kubectl logs -f stag-faust-pr2po-event-sync-64f477675f-2tzzc
: 1609126660:0;kubectl logs -f faust-pr2po-event-sync-d4d574d47-gg97n
: 1609126673:0;kubectl port-forward svc/consul-ui 8501:80
: 1609126760:0;kubectl get po | grep faust
: 1609126772:0;kubectl delete po faust-pr2po-event-sync-d4d574d47-gg97n
: 1609126824:0;kubectl get po | grep faust
: 1609126832:0;kubectl logs -f faust-pr2po-event-sync-d4d574d47-bvfdj
: 1609127650:0;git s
: 1609127655:0;git cm staging
: 1609127671:0;git stash save 'added some test api'
: 1609127672:0;git s
: 1609127675:0;git checkout staging
: 1609127679:0;git stash pop
: 1609127686:0;git s
: 1609127688:0;git a .
: 1609127694:0;git cm 'add some test api'
: 1609127698:0;git s
: 1609128440:0;clear
: 1609128447:0;kubectl get po | grep event-processing-stg
: 1609128467:0;kubectl get po | grep event
: 1609128574:0;kubectl get po | grep fast
: 1609128577:0;kubectl get po | grep faust
: 1609128653:0;kubectl port-forward svc/consul-ui 8501:80
: 1609129355:0;clear
: 1609129540:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609129563:0;export | grep CONFI
: 1609129581:0;CONFIG_NAMESPACE=eventify/dev
: 1609129587:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609131189:0;git status
: 1609131211:0;git add prile/analytics/rfm/rfm_processor.py
: 1609131222:0;git cm 'fix qcut duplicate drop'
: 1609131223:0;git s
: 1609131231:0;git push origin staging
: 1609131246:0;git checkout master
: 1609131255:0;git merge staging
: 1609131260:0;git push origin master
: 1609136959:0;git tree
: 1609137522:0;kubectl get po | grep faust
: 1609140085:0;git s
: 1609140088:0;git a .
: 1609140113:0;git s
: 1609140164:0;git checkout staging
: 1609140166:0;git s
: 1609140168:0;git a .
: 1609140184:0;git cm 'fix attribution max value is 0'
: 1609140184:0;git s
: 1609140190:0;git push origin staging
: 1609140197:0;git
: 1609140205:0;git checkout master
: 1609140205:0;git s
: 1609140216:0;git merge origin staging
: 1609140219:0;git push oir
: 1609140222:0;git push origin
: 1609140983:0;git s
: 1609140992:0;git checkout staging
: 1609140993:0;git s
: 1609141010:0;pip list
: 1609141138:0;git s
: 1609141139:0;git a .
: 1609141150:0;git cm 'remove python-snappy'
: 1609141151:0;git s
: 1609141156:0;git push origin staging
: 1609141171:0;git checkout master
: 1609141178:0;git merge origin staging
: 1609141183:0;git ckeckout staging
: 1609141197:0;git co staging
: 1609141198:0;git s
: 1609141201:0;git tree
: 1609141215:0;git checkout master
: 1609141218:0;git push origin
: 1609141241:0;clear
: 1609143251:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609144108:0;git s
: 1609144111:0;git checkout staging
: 1609144114:0;git s
: 1609144115:0;git a .
: 1609144125:0;git cm 'fix qcut rfm'
: 1609144126:0;git s
: 1609144133:0;git push origin staging
: 1609144143:0;git checkout master
: 1609144149:0;git merge origin staging
: 1609144150:0;git s
: 1609144153:0;git push orgin
: 1609144162:0;git s
: 1609144166:0;git push origin master
: 1609144400:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609144536:0;git s
: 1609144538:0;clear
: 1609144862:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609145929:0;cd prile/batch_processing/orchestration/commands/k8s
: 1609146553:0;clear
: 1609146641:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609146659:0;export | grep CONFI
: 1609146669:0;CONFIG_NAMESPACE=eventify/prod
: 1609146682:0;kubectl port-forward svc/consul-ui 8501:80
: 1609146715:0;export | grep CONFI
: 1609146727:0;cd prile/batch_processing/orchestration/commands/k8s
: 1609147119:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609147131:0;export | grep CONFI
: 1609147150:0;export | grep CONFIG
: 1609147153:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609147450:0;pip list
: 1609147455:0;pip list | grep pandas
: 1609147471:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609148001:0;cd prile/batch_processing/orchestration/commands/k8s
: 1609148243:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609149439:0;clear
: 1609150526:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609150553:0;git s
: 1609150556:0;git a .
: 1609150569:0;git s
: 1609150576:0;git co staging
: 1609150577:0;git s
: 1609150580:0;git a .
: 1609150591:0;git cm 'rewrite qcut'
: 1609150591:0;git s
: 1609150595:0;git push origin
: 1609150601:0;git push origin staging
: 1609150611:0;git checkout master
: 1609150616:0;git merge origin staging
: 1609150620:0;git push origin master
: 1609150683:0;git s
: 1609151412:0;python3 -m prile.batch_processing.pipelines.rfm_updated.rfm_updates
: 1609152445:0;git checkout master
: 1609152447:0;git s
: 1609152459:0;git stash save
: 1609152464:0;git co stagin
: 1609152466:0;git co staging
: 1609152470:0;git stash pop
: 1609153965:0;git s
: 1609153967:0;git a .
: 1609153984:0;git cm 'added string ptraits'
: 1609153987:0;git push origin
: 1609153993:0;git push origin staging
: 1609154003:0;git co master
: 1609154009:0;git merge origin staging
: 1609154013:0;git push origin master
: 1609154054:0;kubectl get po | grep faust
: 1609154312:0;cd prile/batch_processing/orchestration/commands/k8s
: 1609156181:0;git co staging
: 1609156183:0;git a .
: 1609156184:0;git s
: 1609156193:0;git cm 'fix conversion rate ts api'
: 1609156194:0;git s
: 1609156198:0;git push staging
: 1609156207:0;git push origin staging
: 1609156228:0;git co master
: 1609156233:0;git merge origin staging
: 1609156237:0;git push origin master
: 1609215788:0;cd prime
: 1609215788:0;ls
: 1609215814:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1609215826:0;cd ..
: 1609215828:0;docker-compose -f prime/docker-compose.prime.yml up --build
: 1609217437:0;pip install scipy
: 1609218272:0;pip install sklearn
: 1609233219:0;docker-compose -f docker-compose.yml up
: 1609233226:0;docker ps
: 1609233230:0;docker stop $(docker ps -aq)
: 1609233238:0;docker-compose -f docker-compose.yml up
: 1609233246:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609241295:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609253068:0;docker-compose -f docker-compose.yml up
: 1609253073:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609254687:0;git s
: 1609254691:0;git stash save
: 1609254694:0;git checkout staging
: 1609254695:0;git s
: 1609254700:0;git stash pop
: 1609254701:0;git s
: 1609254717:0;git a prile/common/client.py
: 1609254735:0;git a prile/common/data_transforms.py
: 1609254751:0;git a tests/commons/fast_test.py
: 1609254767:0;git a tests/commons/func_common.py
: 1609254777:0;git a tests/prile/common/test_client.py
: 1609254787:0;git a tests/prile/common/test_data_transforms.py
: 1609254788:0;git s
: 1609268928:0;git a .
: 1609268943:0;git cm 'calculate order momentum score'
: 1609268944:0;git s
: 1609268951:0;git push origin staging
: 1609293056:0;docker-compose -f docker-compose.yml up
: 1609293061:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609313604:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609313709:0;git a .
: 1609313711:0;git s
: 1609313738:0;git cm 'order momentum score, campaign engagement score pipeline and api'
: 1609313739:0;git s
: 1609313745:0;git push origin staging
: 1609314083:0;git s
: 1609314090:0;git cm 'score 30 60 90 key'
: 1609314091:0;git s
: 1609314093:0;git a .
: 1609314096:0;git cm 'score 30 60 90 key'
: 1609314097:0;git s
: 1609314100:0;git push origin staging
: 1609314135:0;git s
: 1609314735:0;git pull origin
: 1609314767:0;git s
: 1609314773:0;git pull origin
: 1609314791:0;git stash save
: 1609314795:0;git pull origin
: 1609314824:0;python3 -m prime.generator.gen_specific --api-key _Bfg2IhLQ1vsWYhhoLguNn3018OxT4w6VUK8k1-Jq9I --api-server https://studio.primedata.ai --event-name purchase --threads 2
: 1609314866:0;which python
: 1609314886:0;pip install -r prime/generator/requirements.txt
: 1609314894:0;python3 -m prime.generator.gen_specific --api-key _Bfg2IhLQ1vsWYhhoLguNn3018OxT4w6VUK8k1-Jq9I --api-server https://studio.primedata.ai --event-name purchase --threads 2
: 1609315178:0;git s
: 1609315180:0;clear
: 1609315667:0;git s
: 1609315703:0;git stash save 'move_rfm\
'
: 1609315704:0;git s
: 1609315803:0;git stash save 'rfm'
: 1609315805:0;git s
: 1609315988:0;git a .
: 1609315997:0;git cm 'add score to histogram api'
: 1609315998:0;git s
: 1609316003:0;git push origin staging
: 1609316082:0;python3 -m prime.generator.gen_specific --api-key _Bfg2IhLQ1vsWYhhoLguNn3018OxT4w6VUK8k1-Jq9I --api-server https://studio.primedata.ai --event-name purchase --threads 2
: 1609316109:0;git s
: 1609316770:0;python3 -m prime.generator.gen_specific --api-key _Bfg2IhLQ1vsWYhhoLguNn3018OxT4w6VUK8k1-Jq9I --api-server https://studio.primedata.ai --event-name purchase --threads 2
: 1609320178:0;git s
: 1609320188:0;git stash save 'refactor_rfm'
: 1609320189:0;git s
: 1609320207:0;git cm 'change docker repo'
: 1609320208:0;git s
: 1609320212:0;git a .
: 1609320214:0;git cm 'change docker repo'
: 1609320215:0;git s
: 1609320235:0;git stash pop
: 1609320236:0;git s
: 1609320261:0;git a Dockerfile prile/batch_processing/orchestration/commands/k8s/argo-workflows.yml
: 1609320262:0;git s
: 1609320326:0;git cm 'change docker repo'
: 1609320326:0;git s
: 1609320332:0;git push origin staging
: 1609320342:0;git co master
: 1609320347:0;git merge origin staging
: 1609320354:0;git s
: 1609320360:0;git stash 'save_rfm'
: 1609320360:0;git s
: 1609320366:0;git stash save 'save_rfm'
: 1609320368:0;git s
: 1609320392:0;git co master
: 1609320397:0;git merge origin staging
: 1609320402:0;git push origin master
: 1609320450:0;git s
: 1609320459:0;git stash pop
: 1609320465:0;git s
: 1609320470:0;clear
: 1609320852:0;kubectl get po | grep faust
: 1609320860:0;kubectl logs -f stag-faust-profile-update-7987465d86-nwdqq
: 1609339172:0;docker-compose -f docker-compose.yml up
: 1609339179:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609347517:0;git s
: 1609347521:0;git a .
: 1609347537:0;git cm 'refactor score process'
: 1609347538:0;git s
: 1609347542:0;git push origin master
: 1609347564:0;git co staging
: 1609347565:0;git s
: 1609347570:0;git merge origin master
: 1609347571:0;git s
: 1609347578:0;git push origin staging
: 1609347839:0;python3 -m prile.batch_processing.pipelines.scores
: 1609348030:0;git s
: 1609348033:0;git a .
: 1609348044:0;git cm 'added cron job for scores'
: 1609348045:0;git s
: 1609348049:0;git push origin staging
: 1609383303:0;cd prile/batch_processing/orchestration/commands/k8s
: 1609383400:0;docker-compose -f docker-compose.yml up
: 1609383403:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609384092:0;kubectl get workflowtemplates
: 1609387267:0;python3 - m prile.batch_processing.pipelines.scores
: 1609387290:0;python3 -m prile.batch_processing.pipelines.scores
: 1609388026:0;k get pods
: 1609388030:0;kubectl get pods
: 1609388111:0;kubectl get pod -A cron-daily-scores-update-stag-jn5d4-868577808
: 1609388118:0;kubectl get pod cron-daily-scores-update-stag-jn5d4-868577808
: 1609388255:0;kubectl get pods
: 1609388362:0;kubectl logs cron-daily-scores-update-stag-jn5d4-868577808
: 1609388369:0;kubectl get pods
: 1609388382:0;kubectl logs cron-daily-scores-update-stag-n9kbs-740900182
: 1609388387:0;kubectl logs cron-daily-scores-update-stag-n9kbs-740900182 main
: 1609388629:0;kubectl get pods
: 1609388644:0;kubectl get pods cron-daily-scores-update-stag-xj9dp main
: 1609388657:0;kubectl logs cron-daily-scores-update-stag-xj9dp 
: 1609388661:0;kubectl logs cron-daily-scores-update-stag-xj9dp  main
: 1609388665:0;kubectl logs cron-daily-scores-update-stag-xj9dp wait
: 1609388672:0;kubectl get pods
: 1609388692:0;kubectl logs cron-daily-scores-update-stag-xj9dp wait
: 1609388696:0;kubectl get pods
: 1609388712:0;kubectl logs cron-daily-scores-update-stag-pdw9l main
: 1609388854:0;kubectl get pods -l app=argo-workflow-controller -n argo-system
: 1609388864:0;kubectl get pods -l app=argo-workflow-controller
: 1609388868:0;kubectl get pods -l app=argo-workflow-controller -n argo
: 1609388873:0;kubectl get ns
: 1609388879:0;kubectl get pods -n argo
: 1609389213:0;kubectl get pod -n argo
: 1609389226:0;kubectl get deploy -n argo
: 1609389247:0;kubectl rollout restart deploy workflow-controller
: 1609389254:0;kubectl rollout status deploy workflow-controller
: 1609389260:0;kubectl get pod -n argo
: 1609389293:0;kubectl rollout -n argo restart deploy workflow-controller
: 1609389299:0;kubectl rollout -n argo status deploy workflow-controller
: 1609389303:0;kubectl get pod -n argo
: 1609389312:0;kubectl get deploy
: 1609389342:0;kubectl delete deploy argo-server
: 1609389353:0;kubectl delete deploy workflow-controller
: 1609389362:0;kubectl get pod | grep postgre
: 1609399361:0;clear
: 1609400486:0;git s
: 1609400491:0;git a .
: 1609400516:0;git cm "config algo cron job for score"
: 1609400517:0;git s
: 1609400525:0;git push origin staging
: 1609400586:0;clear
: 1609400594:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609726862:0;docker ps
: 1609726871:0;docker-compose -f docker-compose.yml up
: 1609726887:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609812837:0;docker-compose -f docker-compose.yml up
: 1609812844:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609813011:0;git pull origin staging
: 1609820083:0;git s
: 1609820118:0;git stash save 'segment builder'
: 1609820120:0;git s
: 1609820136:0;git co -b segment-builder
: 1609820149:0;git push origin
: 1609820157:0;git push origin segmen-builder
: 1609820166:0;git push origin segment-builder
: 1609820180:0;git tree
: 1609820420:0;gits
: 1609820421:0;git s
: 1609820429:0;git stash pop
: 1609821940:0;git s
: 1609821951:0;git stash save
: 1609821953:0;git s
: 1609821956:0;git co master
: 1609821970:0;git s
: 1609821975:0;git a .
: 1609821982:0;git cm 'edited docker file'
: 1609821985:0;git push origin master
: 1609822017:0;git co segment-builder
: 1609822021:0;git stash pop
: 1609832494:0;git s
: 1609832496:0;git a .
: 1609832497:0;git cm 
: 1609832504:0;git s
: 1609832512:0;git cm 'segment buider'
: 1609832517:0;git push origin segment-builder
: 1609832560:0;git pull origin segment-builder
: 1609832572:0;git push origin segment-builder
: 1609836729:0;git s
: 1609837214:0;git clone git@github.com:primedata-ai/Seplat.git
: 1609839526:0;git s
: 1609839533:0;git a .
: 1609839552:0;git cm 'added segment builder models'
: 1609839553:0;git s
: 1609845127:0;git a .
: 1609845143:0;git cm 'added segment builder parser'
: 1609845143:0;git s
: 1609845150:0;git push origin segment-builder
: 1609845161:0;git pull origin segment-builder
: 1609845171:0;git s
: 1609845176:0;git push origin segment-builder
: 1609846091:0;git s
: 1609846845:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609847446:0;git s
: 1609847448:0;git a .
: 1609847456:0;git cm 'expose api for segment'
: 1609847457:0;git s
: 1609900126:0;docker-compose -f docker-compose.yml up
: 1609900131:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609900136:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609901972:0;git pull origin
: 1609901984:0;git pull origin segment-builder
: 1609902039:0;git s
: 1609924872:0;git a .
: 1609924909:0;git cm 'added tenant_id, did not performed, add tests'
: 1609924910:0;git s
: 1609924915:0;git push origin segment-builder
: 1609932780:0;git a .
: 1609932811:0;git cm 'added test funnel and bool parser'
: 1609932812:0;git s
: 1609932818:0;git pull origin segment-builder
: 1609932931:0;git s
: 1609934012:0;git cm 'added Within class'
: 1609934012:0;git s
: 1609934020:0;git push origin segment-builder
: 1609986445:0;git s
: 1609986482:0;git a .
: 1609986500:0;git cm 'modified window time in parser'
: 1609986501:0;git s
: 1609986506:0;git push origin segment-builder
: 1609986546:0;git pull origin segment-builder
: 1609986730:0;git s
: 1609986736:0;git a .
: 1609986753:0;git cm 'moved segment builder file to a module'
: 1609986754:0;git s
: 1609986759:0;git push origin segment-builder
: 1609986768:0;git s
: 1609989781:0;git a .
: 1609989820:0;git cm 'got property type from front end'
: 1609989821:0;git s
: 1609989827:0;git push origin segment-builder
: 1609989854:0;git s
: 1609990356:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609990362:0;docker-compose -f docker-compose.yml up
: 1609990369:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1609990375:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1609994014:0;git s
: 1609994035:0;git a .
: 1609994045:0;git cm 'expose get segment size api'
: 1609994046:0;git s
: 1609994050:0;git push origin segment
: 1609994053:0;git push origin segment-by
: 1609994057:0;git push origin segment-builder
: 1610005138:0;git s
: 1610005156:0;git stash save
: 1610005160:0;git co staging
: 1610005161:0;git s
: 1610005245:0;git stash pop
: 1610005246:0;git s
: 1610005249:0;git a .
: 1610005258:0;git cm 'update sql'
: 1610005259:0;git s
: 1610005409:0;git co -b remove_segment_size
: 1610005410:0;git s
: 1610005789:0;git co staging
: 1610005817:0;git s
: 1610005822:0;git co segment-builder
: 1610005823:0;git s
: 1610006712:0;which python
: 1610006726:0;cd ..
: 1610006744:0;cd PYTHON
: 1610006747:0;cd .python3
: 1610006747:0;s
: 1610006748:0;ls
: 1610006750:0;cd bin
: 1610006751:0;ls
: 1610006760:0;source ./activate
: 1610006762:0;clear
: 1610006789:0;pip install jsonschema
: 1610012903:0;git s
: 1610013246:0;git co master
: 1610013332:0;git merge orgin staging
: 1610013337:0;git merge origin staging
: 1610013358:0;git co staging
: 1610013366:0;git merge master
: 1610013380:0;git push origin staging
: 1610013393:0;git pull origin staging
: 1610013427:0;git push origin staging
: 1610013601:0;git co master
: 1610013604:0;git push origin master
: 1610013635:0;git co segment-builder
: 1610013647:0;git pull origin segment-builder
: 1610013663:0;gi ts
: 1610013664:0;git s
: 1610013826:0;kubectl get pods | grep cron-daily
: 1610013949:0;git s
: 1610013953:0;git stash save
: 1610013969:0;git co staging
: 1610013972:0;git stash pop
: 1610013979:0;git s
: 1610013984:0;git a .
: 1610014008:0;git cm 'fixed argo job remove log if run success'
: 1610014009:0;git s
: 1610014196:0;kubectl get po | grep faust
: 1610014286:0;kubectl logs -f stag-faust-conversion-broadcast-69894974c8-984q5
: 1610014525:0;python3 - m prile.batch_processing.pipelines.scores
: 1610014537:0;python3 -m prile.batch_processing.pipelines.scores
: 1610014662:0;git s
: 1610014691:0;python3 -m prile.batch_processing.pipelines.scores
: 1610014861:0;kubectl logs -f stag-faust-conversion-broadcast-69894974c8-984q5
: 1610015183:0;kubectl get po | grep faust
: 1610015223:0;kubectl delete deployment stag-faust-conversion-broadcast
: 1610015238:0;faust -A prile.workflows.conversion_broadcast.app pipelines -l info -p 6068
: 1610015326:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1610015845:0;kubectl port-forward svc/consul-ui 8501:80
: 1610015994:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1610016067:0;git s
: 1610016068:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1610016072:0;git s
: 1610016140:0;git a .
: 1610016140:0;git s
: 1610016177:0;git cm 'fixed ptrait topic not recieve'
: 1610016178:0;git s
: 1610016182:0;git push origin staging
: 1610016512:0;git s
: 1610016890:0;git co segment-builder
: 1610074273:0;git s
: 1610074287:0;git a .
: 1610074307:0;git cm 'added test for parse function'
: 1610074308:0;git s
: 1610074312:0;git push origin segment-builder
: 1610076941:0;docker-compose -f docker-compose.yml up
: 1610076947:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1610076959:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1610077069:0;python3 - m prile.batch_processing.pipelines.scores
: 1610077089:0;git s
: 1610077093:0;git co staging
: 1610077095:0;git s
: 1610077102:0;python3 -m prile.batch_processing.pipelines.scores
: 1610077143:0;clear
: 1610077244:0;git s
: 1610077245:0;claer
: 1610077248:0;clear
: 1610077262:0;git s
: 1610077268:0;git co segment-builder
: 1610077269:0;git s
: 1610077358:0;git pull origin segmentb
: 1610077363:0;git pull origin segment-builder
: 1610078045:0;clear
: 1610078738:0;git s
: 1610078741:0;git a l
: 1610078754:0;git cm 'move files into segment module'
: 1610078755:0;git s
: 1610078760:0;git push origin segment-builder
: 1610079524:0;git s
: 1610079543:0;git a .
: 1610079546:0;git cm 'move files into segment module'
: 1610079548:0;git push origin segment-builder
: 1610080957:0;clear
: 1610081129:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1610081360:0;git s
: 1610081538:0;git a .
: 1610081562:0;git cm 'added DTO segment size to reponse"\
'
: 1610081562:0;git s
: 1610081569:0;git push origin segment-builder
: 1610082253:0;git a .
: 1610082332:0;git cm 'fixed case if a condition then tree not have or condition'
: 1610082333:0;git s
: 1610082339:0;git push origin segment-builder
: 1610092636:0;clear
: 1610092642:0;kubectl get po grep | faust
: 1610092647:0;kubectl get po grep | grep faust
: 1610092655:0;kubectl get po | grep faust
: 1610092751:0;faust -A prile.workflows.conversion_broadcast.app pipelines -l info -p 6068
: 1610092762:0;git co setaging
: 1610092765:0;git co staging
: 1610092766:0;git s
: 1610092771:0;faust -A prile.workflows.conversion_broadcast.app worker -l info -p 6068
: 1610093697:0;kubectl get po | grep faust
: 1610093713:0;git co segment-builder
: 1610093714:0;git s
: 1610094687:0;git pull origin segment-builder
: 1610095237:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1610098306:0;git s
: 1610098317:0;git a .
: 1610098339:0;git cm 'segment builder: interage with queries builder\
'
: 1610098340:0;git s
: 1610098637:0;git a .
: 1610098779:0;git cm 'added self to super() function'
: 1610098780:0;git s
: 1610098784:0;git push origin segment-builder
: 1610098794:0;git pull origin segment-builder
: 1610098807:0;git push origin segment-builder
: 1610098815:0;git s
: 1610100260:0;git a .
: 1610100290:0;git cm "added nested string to property value"
: 1610100291:0;git s
: 1610100298:0;git push origin segment-builder
: 1610101542:0;git s
: 1610101543:0;git a .
: 1610101559:0;git cm 'added step id into FunnelStepNode'
: 1610101560:0;git s
: 1610101564:0;git push origin segment-builder
: 1610101586:0;clear
: 1610163108:0;git s
: 1610163109:0;git a .
: 1610163120:0;git cm 'back up'
: 1610163126:0;git push origin master
: 1610163146:0;git s
: 1610163171:0;git a .
: 1610163186:0;git s
: 1610163189:0;git a .
: 1610163192:0;git cm 'back up'
: 1610163195:0;git s
: 1610163201:0;git push origin master
: 1610163262:0;git s
: 1610163263:0;git a .
: 1610163265:0;git s
: 1610163271:0;git push origin master
: 1610163319:0;git init
: 1610163324:0;git a .
: 1610163331:0;[200~git commit -m "first commit"~
: 1610163341:0;git commit -m "first commit"
: 1610163347:0;git cm 'first cm'
: 1610163348:0;git s
: 1610163359:0;git remote add origin https://github.com/levanchi74/PYTHON.git
: 1610163365:0;git push -u origin main
: 1610163377:0;clear
: 1610163706:0;htop
: 1610163761:0;df
: 1610163860:0;sudo apt autoremove
: 1610163883:0;sudo apt autoclean
: 1610163953:0;htop
: 1610163982:0;clear
: 1610164120:0;kubectl get po | grep faust
: 1610164143:0;docker-compose -f docker-compose.yml up
: 1610164149:0;sudo openvpn --config ~/Documents/pem/chile-118.68.168.185.ovpn
: 1610164154:0;uvicorn main:app --reload --host 0.0.0.0 --port 8899
: 1610164157:0;kubectl get po | grep faust
: 1610176721:0;git a .
: 1610176741:0;git cm 'tested compile_trait_condition query and fix some bug'
: 1610176742:0;git s
: 1610176746:0;git push origin segment-builder
: 1610176755:0;git pull origin segment-builder
: 1610176938:0;git s
: 1610176940:0;git a .
: 1610176948:0;git cm "merged with origin"
: 1610176953:0;git push origin segment-builder
: 1610177421:0;git a .
: 1610177439:0;git cm 'FunnelStep now is a Node'
: 1610177440:0;git s
: 1610177446:0;git push origin segment-builder
: 1610283506:0;htop
: 1610283540:0;sudo apt-get update
: 1610336187:0;history
: 1610339140:0;cd ~/
: 1610339140:0;ls
: 1610339143:0;ls -la
: 1610339155:0;gedit .zsh_history
