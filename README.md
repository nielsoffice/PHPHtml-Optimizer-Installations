<h5>Table of Content</h5>
<a href="#FolderStructure"> - Folder Structure</a><br />
<a href="#DownloadingPHPHtml-Optimizer"> - Downloading PHPHtml-Optimizer</a><br />
<a href="#InstallingPHPHtml-Optimizer"> - Installing PHPHtml-Optimizer</a><br />
<a href="#Instantiate"> - Using Class Static and Instantiate</a><br />
<a href="#QuickStart"> - Quick Start Instantate Classes</a><br />
<a href="#WordPressInstallation"> - WordPress Installation</a><br />
<a href="#WordPressInstallation"> - WordPress USAGE  </a><br />
<a href="#Drupal"> - Drupal Installation </a><br />
<a href="#Joomla"> - Joomla Installation </a><br />
<a href="#Magento"> - Magento 2 Installation </a><br />
<a href="#CodeIgniter"> - CodeIgniter Installation  </a><br />
<a href="#LaravelCodeIgniter"> - Laravel Installation  </a><br />

<h4 id="FolderStructure">Folder Structure</h4>

```PHP

|- root folder
  |- library
    |- PHPHtml-Optimizer
       |- optimizer
       |- merge
       |- PHPHtml-optimizer.php
       |- prop.php
  |- includes
  |- portfolio.php
  |- index.php
  |- etc...

```

<h4 id="DownloadingPHPHtml-Optimizer">Downloading PHPHtml-Optimizer</h4>

```PHP

// Run Command line directory with your project folder
~ C:/path/www/project/Library/ 

// Run command
~ composer require phphtml-optimizer/phphtml-optimizer	

```

<h6 id="InstallingPHPHtml-Optimizer">Installing PHPHtml-Optimizer</h6>

```PHP

// On the very top of your header.php file
require_once __DIR__ . '/library/PHPHtml-Optimizer/PHPHtml-Optimizer.php';

```

<h6 id="Instantiate">Using Class Static and Instantiate</h6>

```PHP

// Static Default
USE \PHPHtml\CodeOptimizer\merge\Html; 

// Static Alias
USE \PHPHtml\CodeOptimizer\merge\Html AS MyHTML;

// Instantiate Default
$html = NEW \PHPHtml\CodeOptimizer\optimizer\Html(); 

// Instantiate Alias
USE \PHPHtml\CodeOptimizer\optimizer\Html AS MyElement; 

// Instantiate Default
$Enhancer = NEW \PHPHtml\CodeOptimizer\optimizer\Enhancers(); 

// Instantiate Alias
USE \PHPHtml\CodeOptimizer\optimizer\Enhancers AS OptimizerCar();

```

<h4>Reference: directories.php </h4>

```PHP

 |- root/Theme : 
   |- Library 
     |- PHPHtml-Optimizer
   |- index.php
   |- portfolio.php
   |- config.php       

 <?php $Care = NEW \PHPHtml\CodeOptimizer\optimizer\Enhancers(); ?>
 <?php 
 
 ...

```

<h6 id="QuickStart">Quick Start Instantate Classes </h6>

```PHP

// Usages: files/pages.php<br />
USE \PHPHtml\CodeOptimizer\merge\Html;
USE \PHPHtml\CodeOptimizer\optimizer\Html AS Optimizer;
USE \PHPHtml\CodeOptimizer\optimizer\Enhancers AS OptimizerCare;

$html        = NEW Optimizer();
$fileEnhance = NEW OptimizerCare();	
...

```

<h6 id="WordPressInstallation">WordPress Installation </h6>

```PHP
// Download WordPress via Composer then Open Shell Create project folder run snippet code
composer require roots/wordpress

// Copy paste this line of codes on your functions.php theme file
require_once __DIR__ . '/library/PHPHtml-Optimizer/PHPHtml-Optimizer.php'; 

|- wp-content
  |- Theme
     |- YourTheme
       |- library // Create folder named library 
         |- PHPHtml-Optimizer
           |- optimizer
           |- merge
           |- PHPHtml-optimizer.php
           |- prop.php
       |- includes
       |- page.php
       |- single.php
       |- index.php
       |- etc..

```

<h6 id="wpUSAGE">WordPress Installation | USAGE: files/pages.php </h6>	

```PHP

USE \PHPHtml\CodeOptimizer\merge\Html;
USE \PHPHtml\CodeOptimizer\optimizer\Html AS Optimizer;
USE \PHPHtml\CodeOptimizer\optimizer\Enhancers AS OptimizerCare;

$Html = NEW Optimizer();
$FileEnhance = NEW OptimizerCare();	

// your code goes here ...

```

<h6 id="Drupal">Drupal Installation </h6>

```PHP

...

```

<h6 id="Joomla">Joomla Installation </h6>

```PHP

...

```

<h6 id="Magento">Magento 2 Installation </h6>

```PHP

...

```

<h6 id="CodeIgniter">CodeIgniter Installation </h6>

```PHP

...

```

<h6 id="Laravel">Laravel Installation </h6>

```PHP

...

```

For PHPOptimizer more examples and <a href="https://github.com/nielsofficeofficial/PHPHtml-Optimizer-Docx"> Documentation link here </a><br /> 
For PHPFileEnhancers and <a href="https://github.com/nielsofficeofficial/PHPHtml-Optimizer-Enhancers"> Reference link here </a><br /> 
For PHPMaintenance Mode and <a href="#"> SOON on <i>PHPHtml-Optimizer</i> v1.4 </a><br />
For PHPForm and <a href="#"> SOON on <i>PHPHtml-Optimizer</i> v1.4 </a><br /> 
For Html to PHPHtml-Optimizer Generator(Converter) <a href="#"> SOON <i> Convert HTML to PHPHtml-Optimizer Premium</i></a><br /> 
For Developer <a href="https://github.com/nielsofficeofficial/PHPHtml-Optimizer/issues"> Support link here </a><br /> 
This Library is 100% secured and fully free ready to use, If you see vulnerability you can email me: @ nieldigitalsolution@gmail.com

<h2>Thanks To:</h2>
<h5>
Github : To allow me to upload my PHPHtml-Optimizer PHP Library to repository<br /> 
php.net : To oppurtunity Develop web application using corePHP - PHPFrameworks<br />
w3school : HTML Elements reference</h5>

__For Suggestion and Donation/Sponsorship You can send via GCash : +639650332900__ <br /> __Also You can send via Paypal account: syncdevprojects@gmail.com__ <br /> Thanks and good luck! 


