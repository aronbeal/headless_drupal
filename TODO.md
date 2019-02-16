# Solution

## Packages

- [Ember Waterwheel (Acquia)](https://github.com/acquia/ember-drupal-waterwheel)
- Drupal minimal installation (manually enable seven theme)
    - Need to disable the Administration menu block for seven theme at /admin/structure/block/list/seven
- [Simple OAuth](https://www.drupal.org/project/simple_oauth)
- [Cors](https://www.drupal.org/project/cors)
- [JSONAPI](https://www.drupal.org/project/jsonapi)

## Local development

- [docker-ember](https://github.com/sergiolepore/docker-ember#docker-compose-examples) used for container development.
    - Version of docker-ember used was based on the Node [support matrix](https://github.com/ember-cli/ember-cli/blob/master/docs/node-support.md)
    - Note: need to [mount the ddev folder as a separate mount point](https://stackoverflow.com/questions/29181032/add-a-volume-to-docker-but-exclude-a-sub-folder), due to the folder co-location.
- 

# List of TODO items

- Restrict values in web/sites/default/services.yml: `allowedOrigins`.
- 