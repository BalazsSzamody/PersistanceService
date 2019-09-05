FROM swift:5.0

LABEL "com.github.actions.name"="Swift Package Test"
LABEL "com.github.actions.description"="Run Swift Package tests"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="http://github.com/BalazsSzamody/PersistanceService"
LABEL "homepage"="http://github.com/BalazsSzamody"
LABEL "maintainer"="Balazs <fr3qfly@gmail.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
