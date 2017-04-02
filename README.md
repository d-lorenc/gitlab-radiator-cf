# gitlab-radiator-cf

CF deployable [gitlab-radiator](https://www.npmjs.com/package/gitlab-radiator)

### Config / Push

Just add access token to [.gitlab-radiator.yml](.gitlab-radiator.yml) and `cf push` to your favourite instance of the cloud foundry.

You may want to remove `random-route` from the [manifest.yml](manifest.yml) and give your app a unique name if you don't like the randomized name/url. 

Also change the `url` in [.gitlab-radiator.yml](.gitlab-radiator.yml) if your repos are not on https://gitlab.com (default).
