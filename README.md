## Apache

  helmfile diff -f apache-helmfile.yaml \
    --state-values-set namespace=ns........... \
    --state-values-set baseDomain=domain.........

## MariaDb

  helmfile diff -f mariadb-helmfile.yaml \
    --state-values-set namespace=ns........... \
    --state-values-set database=db.......... \
    --state-values-set rootPassword=pass.........

## PhpMyAdmin

  helmfile diff -f phpmyadmin-helmfile.yaml \
    --state-values-set namespace=ns........... \
    --state-values-set baseDomain=domain.........
    --state-values-set dbHost=host.........