# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# NOTE: DO *NOT* EDIT THIS FILE.  IT IS GENERATED.
# PLEASE UPDATE Dockerfile.txt INSTEAD OF THIS FILE
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
FROM selenium/base:4.0.0-alpha-7-prerelease-20201009
LABEL authors=SeleniumHQ

USER 1200

#========================
# Selenium SessionQueuer Configuration
#========================

EXPOSE 5559

COPY start-selenium-grid-sessionqueuer.sh \
    /opt/bin/

COPY selenium-grid-sessionqueuer.conf /etc/supervisor/conf.d/
