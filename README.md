# 2309_wordpress_plugin_featured_professor

## Install Wordpress Javascript package

> create package.json -> npm init -y
> npm i @wordpress/scripts

## Get wordpress database data

> wp.data.select("core").getEntityRecords("postType","professor", {per_page: -1})

## Get React wordpress database data

> index.js -> import {useSelect} from "@wordpress/data"
> select("core").getEntityRecords("postType","professor", {per_page: -1})
