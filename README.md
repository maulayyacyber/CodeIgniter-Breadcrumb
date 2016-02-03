# CodeIgniter-Breadcrumb

## Instalation

* put this file Breadcrumb.php to folder application/library in your project CodeIgniter
* change auto load libraries in applications/config/autoload.php

## Example Use This BreadCrumb

* // load library breadcrumb
	$this->breadcrumb->append_crumb('','Dashboard', base_url().'admin/dashboard');
  $this->breadcrumb->append_crumb('current','Link Terkait', '#');

* //view this breadcrumb 
* <?php print $this->breadcrumb->output(); ?> 

Library Breadcrumb CodeIgniter
