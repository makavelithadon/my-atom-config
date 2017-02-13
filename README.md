# my-atom-config

## Getting started

```
git clone url_to_repository
```


## run from command line on old install :

``````
apm list --installed --bare > packages.list
``````

## then you do from the command line on your new install

``````
apm install `cat packages.list`
``````
