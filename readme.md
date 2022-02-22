# Install the latest version of yandex cloud cli

## Example usage

```yaml
- name: Try to install yc cli and login into yandex cloud
  uses: okar1/yc-cli-install@master
  with:
    SA_KEY: your service account private key (json form) [optional]

```

***(eng)*** This will install the latest version of yandex cloud cli. Then logging in if SA_KEY parameter is provided.

***(rus)*** Устанавливает последнюю версию yc cli. Выполняет логин если указан SA_KEY.


## Outputs

none
