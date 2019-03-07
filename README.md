# odoo_docker
Docker setup for easy Odoo development

Based on https://github.com/odoo/docker

Most config is done in `.env`

For running Odoo 12 Enterprise you need to have a valid licence and download the file (odoo_12.0+e.latest_all.deb) yourself. Then build your own **local** image by running `docker build -t odoo:12e .`
