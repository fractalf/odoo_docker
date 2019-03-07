# odoo_docker
Docker setup for easy Odoo development

Based on https://github.com/odoo/docker

Most config is done in `.env`

For running Odoo 12 Enterprise you need to have a valid licence and download the file (odoo_12.0+e.latest_all.deb) yourself. Then build your own **local** image by running `docker build -t odoo:12e .`

If you need to run 2 (or more) setups with different versions (or not) just edit these variables in the `.env` file
* COMPOSE_PROJECT_NAME
* CONTAINER_NAME_ODOO
* CONTAINER_NAME_DB
* PORT_PREFIX
* ODOO_MODULES

Note: If you need to develop two parallell systems on the same code base (same repo) you might want to work on two seperate folders containing the same repo.
