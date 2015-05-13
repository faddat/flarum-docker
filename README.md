# Flarum Docker image

If you want to have flarum running on docker, and you're not too concerned with how, a great way to do it is as follows:

```bash
vagrant plugin install docker
git clone https://github.com/flarum/flarum
cd flarum
vagrant up --provider docker
```

Should do the trick.  




