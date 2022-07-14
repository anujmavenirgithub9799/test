# yala docker build -f yalaconfig
# yala docker push -f yalaconfig

# helm package helm/charts/mavenir-config/

# curl -H "X-JFrog-Art-Api:YOURAPIKEYHERE" -T mavenir-config-2.4.6.tgz "https://artifactory.mavenir.com/artifactory/ngn-mwpcicd-dev/RELEASE-2.4.6/mavenir-config-2.4.6.tgz"

# curl -H "X-JFrog-Art-Api:YOURAPIKEYHERE" -T  environment-files/setups/single-db.yaml "https://artifactory.mavenir.com/artifactory/ngn-mwpcicd-dev/RELEASE-2.4.6/environment-files/setups/single-db.yaml"

# curl -H "X-JFrog-Art-Api:YOURAPIKEYHERE" -T  environment-files/setups/registry.only.yaml "https://artifactory.mavenir.com/artifactory/ngn-mwpcicd-dev/RELEASE-2.4.6/environment-files/setups/registry.only.yaml"

# curl -H "X-JFrog-Art-Api:YOURAPIKEYHERE" -T  environment-files/setups/highly-available.yaml "https://artifactory.mavenir.com/artifactory/ngn-mwpcicd-dev/RELEASE-2.4.6/environment-files/setups/highly-available.yaml"

# curl -H "X-JFrog-Art-Api:YOURAPIKEYHERE" -T  environment-files/setups/dedicated-dbs.yaml "https://artifactory.mavenir.com/artifactory/ngn-mwpcicd-dev/RELEASE-2.4.6/environment-files/setups/dedicated-dbs.yaml"

# curl -H "X-JFrog-Art-Api:YOURAPIKEYHERE" -T  environment-files/yalaconfig.yaml "https://artifactory.mavenir.com/artifactory/ngn-mwpcicd-dev/RELEASE-2.4.6/environment-files/yalaconfig.yaml"

# curl -H "X-JFrog-Art-Api:YOURAPIKEYHERE" -T  environment-files.tar.gz "https://artifactory.mavenir.com/artifactory/ngn-mwpcicd-dev/RELEASE-2.4.6/environment-files.tar.gz"