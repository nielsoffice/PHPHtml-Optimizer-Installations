<h4>Installing PHPHtml-Optimizer</h4>
<pre>

// Require file in header file or in every page where you will use.
require_once (__DIR__ . '/library/PHPHtml-Optimizer/PHPHtml-Optimizer.php');

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

</pre>