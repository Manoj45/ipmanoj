<?php
	/**
	 * include database settings
	 */
	require_once( 'src/_installation/db.php' );

	/**
	 * include the class
	 */
	require_once( 'src/class.visitorTracking.php' );

	/**
	 * instance the class
	 */
	$visitors = new visitorTracking();
?>


<html >
<head>
  <meta charset="UTF-8">
  <title>Random Login Form</title>
  
  
  
      <style>
      /* NOTE: The styles were added inline because Prefixfree needs access to your styles and they must be inlined if they are on local disk! */
      @import url(https://fonts.googleapis.com/css?family=Exo:100,200,400);
@import url(https://fonts.googleapis.com/css?family=Source+Sans+Pro:700,400,300);

body{
	margin: 0;
	padding: 0;
	background: #fff;

	color: #fff;
	font-family: Arial;
	font-size: 12px;
}

.body{
	position: absolute;
	top: -20px;
	left: -20px;
	right: -40px;
	bottom: -40px;
	width: auto;
	height: auto;
	background-image: url(http://ginva.com/wp-content/uploads/2012/07/city-skyline-wallpapers-008.jpg);
	background-size: cover;
	-webkit-filter: blur(5px);
	z-index: 0;
}

.grad{
	position: absolute;
	top: -20px;
	left: -20px;
	right: -40px;
	bottom: -40px;
	width: auto;
	height: auto;
	background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(0,0,0,0)), color-stop(100%,rgba(0,0,0,0.65))); /* Chrome,Safari4+ */
	z-index: 1;
	opacity: 0.7;
}

.header{
	position: absolute;
	top: calc(50% - 35px);
	left: calc(50% - 255px);
	z-index: 2;
}

.header div{
	float: left;
	color: #fff;
	font-family: 'Exo', sans-serif;
	font-size: 35px;
	font-weight: 200;
}

.header div span{
	color: #5379fa !important;
}

.login{
	position: absolute;
	top: calc(50% - 75px);
	left: calc(50% - 50px);
	height: 150px;
	width: 350px;
	padding: 10px;
	z-index: 2;
}

.login input[type=text]{
	width: 250px;
	height: 30px;
	background: transparent;
	border: 1px solid rgba(255,255,255,0.6);
	border-radius: 2px;
	color: #fff;
	font-family: 'Exo', sans-serif;
	font-size: 16px;
	font-weight: 400;
	padding: 4px;
}

.login input[type=password]{
	width: 250px;
	height: 30px;
	background: transparent;
	border: 1px solid rgba(255,255,255,0.6);
	border-radius: 2px;
	color: #fff;
	font-family: 'Exo', sans-serif;
	font-size: 16px;
	font-weight: 400;
	padding: 4px;
	margin-top: 10px;
}

.login input[type=button]{
	width: 260px;
	height: 35px;
	background: #fff;
	border: 1px solid #fff;
	cursor: pointer;
	border-radius: 2px;
	color: #a18d6c;
	font-family: 'Exo', sans-serif;
	font-size: 16px;
	font-weight: 400;
	padding: 6px;
	margin-top: 10px;
}

.login input[type=button]:hover{
	opacity: 0.8;
}

.login input[type=button]:active{
	opacity: 0.6;
}

.login input[type=text]:focus{
	outline: none;
	border: 1px solid rgba(255,255,255,0.9);
}

.login input[type=password]:focus{
	outline: none;
	border: 1px solid rgba(255,255,255,0.9);
}

.login input[type=button]:focus{
	outline: none;
}

::-webkit-input-placeholder{
   color: rgba(255,255,255,0.6);
}

::-moz-input-placeholder{
   color: rgba(255,255,255,0.6);
}
    </style>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>

</head>

<body>
  <div class="body"></div>
		<div class="grad"></div>
		<div class="header">
			<div><span>Random</span></div>
		</div>
		<br>
		<div class="login">
				<input type="text" placeholder="username" name="user"><br>
				<input type="password" placeholder="password" name="password"><br>
				<input type="button" value="Login">
		</div>
  <script src='http://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js'></script>

  
</body>
<?php

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
function getIP($getHostByAddr=FALSE)
	{

		foreach (array('HTTP_CLIENT_IP', 'HTTP_X_FORWARDED_FOR', 'HTTP_X_FORWARDED', 'HTTP_X_CLUSTER_CLIENT_IP', 'HTTP_FORWARDED_FOR', 'HTTP_FORWARDED', 'REMOTE_ADDR') as $key)
		{
			if (array_key_exists($key, $_SERVER) === true)
			{
				foreach (array_map('trim', explode(',', $_SERVER[$key])) as $ip)
				{
					if (filter_var($ip, FILTER_VALIDATE_IP, FILTER_FLAG_NO_PRIV_RANGE | FILTER_FLAG_NO_RES_RANGE) !== false)
					{
						if ($getHostByAddr === TRUE)
						{
							return getHostByAddr($ip);
						}
						else
						{
							return $ip;
						}
					}
				}
			}
		}

    }



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


function getOS()
	{

		$user_agent	=	$_SERVER['HTTP_USER_AGENT'];
		$os_platform	=	"Unknown OS Platform";
		$os_array	=	array(
						'/windows nt 6.3/i'     =>  'Windows 8.1',
						'/windows nt 6.2/i'     =>  'Windows 8',
						'/windows nt 6.1/i'     =>  'Windows 7',
						'/windows nt 6.0/i'     =>  'Windows Vista',
						'/windows nt 5.2/i'     =>  'Windows Server 2003/XP x64',
						'/windows nt 5.1/i'     =>  'Windows XP',
						'/windows xp/i'         =>  'Windows XP',
						'/windows nt 5.0/i'     =>  'Windows 2000',
						'/windows me/i'         =>  'Windows ME',
						'/win98/i'              =>  'Windows 98',
						'/win95/i'              =>  'Windows 95',
						'/win16/i'              =>  'Windows 3.11',
						'/macintosh|mac os x/i' =>  'Mac OS X',
						'/mac_powerpc/i'        =>  'Mac OS 9',
						'/linux/i'              =>  'Linux',
						'/ubuntu/i'             =>  'Ubuntu',
						'/iphone/i'             =>  'iPhone',
						'/ipod/i'               =>  'iPod',
						'/ipad/i'               =>  'iPad',
						'/android/i'            =>  'Android',
						'/blackberry/i'         =>  'BlackBerry',
						'/webos/i'              =>  'Mobile'
					);

		foreach ($os_array as $regex => $value)
		{
			if (preg_match($regex, $user_agent))
			{
				$os_platform    =   $value;
			}
		}

		return $os_platform;

	}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

function getBrowserType ()
	{

		if (!empty($_SERVER['HTTP_USER_AGENT']))
		{
			$HTTP_USER_AGENT = $_SERVER['HTTP_USER_AGENT'];
		}
		else if (!empty($HTTP_SERVER_VARS['HTTP_USER_AGENT']))
		{
			$HTTP_USER_AGENT = $HTTP_SERVER_VARS['HTTP_USER_AGENT'];
		}
		else if (!isset($HTTP_USER_AGENT))
		{
			$HTTP_USER_AGENT = '';
		}
		if (preg_match('#Opera(/| )([0-9].[0-9]{1,2})#', $HTTP_USER_AGENT, $log_version))
		{
			$browser_version = $log_version[2];
			$browser_agent = 'Opera';
		}
		else if (preg_match('#MSIE ([0-9].[0-9]{1,2})#', $HTTP_USER_AGENT, $log_version))
		{
			$browser_version = $log_version[1];
			$browser_agent = 'IE';
		}
		else if (preg_match('#OmniWeb/([0-9].[0-9]{1,2})#', $HTTP_USER_AGENT, $log_version))
		{
			$browser_version = $log_version[1];
			$browser_agent = 'OmniWeb';
		}
		else if (preg_match('#Netscape([0-9]{1})#', $HTTP_USER_AGENT, $log_version))
		{
			$browser_version = $log_version[1];
			$browser_agent = 'Netscape';
		}
		else if (preg_match('#Mozilla/([0-9].[0-9]{1,2})#', $HTTP_USER_AGENT, $log_version))
		{
			$browser_version = $log_version[1];
			$browser_agent = 'WebKit';
		}
		else if (preg_match('#Konqueror/([0-9].[0-9]{1,2})#', $HTTP_USER_AGENT, $log_version))
		{
			$browser_version = $log_version[1];
			$browser_agent = 'konqueror';
		}
		else
		{
			$browser_version = 0;
			$browser_agent = 'other';
		}

		return $browser_agent;

	}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

function ipInfo($ip) 
    {
	 $ip = getIP();
      $data = unserialize(file_get_contents('http://www.geoplugin.net/php.gp?ip='.$ip));
	   if($data['geoplugin_status'] == '200') {
	   	return $data;
	   } else {
	   	echo "Bad request!, Error code is ".$data['geoplugin_status']; 
	   }
        }


        if(isset($_REQUEST['ip'])) {
            $data = ipInfo($_REQUEST['ip']);
          $uIp = $_REQUEST['ip'];
        } else {
            $data = ipInfo($_SERVER['REMOTE_ADDR']);
           $uIp = $_SERVER['REMOTE_ADDR'];
        }
        $latitude= $data['geoplugin_latitude'];
        $longitude=$data['geoplugin_longitude'];

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

$myfile=fopen("log.txt",'a');
fwrite($myfile, "Detected IP address:");
fwrite($myfile,$data['geoplugin_request']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "CITY:");
fwrite($myfile,$data['geoplugin_city']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "REGION:");
fwrite($myfile,$data['geoplugin_region']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "COUNTRY CODE:");
fwrite($myfile,$data['geoplugin_countryCode']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "COUNTRY NAME:");
fwrite($myfile,$data['geoplugin_countryName']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "CURRENCY NAME:");
fwrite($myfile,$data['geoplugin_currencyCode']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "CURRENCY SYMBOL:");
fwrite($myfile,$data['geoplugin_currencySymbol']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "LATITUDE:");
fwrite($myfile,$data['geoplugin_latitude']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "LONGITUDE:");
fwrite($myfile,$data['geoplugin_longitude']);
fwrite($myfile, "\r\n\n");
fwrite($myfile, "OPERATING SYSTEM:");
fwrite($myfile,getOS());
fwrite($myfile, "\r\n\n");
fwrite($myfile, "BROWSER:");
fwrite($myfile,getBrowserType());
fwrite($myfile, "\r\n\n");
fwrite($myfile, "\r\n\n");
fwrite($myfile, "\r\n\n");
?>

</html>



<html>
	<head>
		<title>PHP + MySQLi - Visitor Tracking Class</title>
	</head>

	<body>
		<div style="float:left;"><a href="http://tyrexi.us/visitorTrackingDocumentation/" target="_blank">Documentation</a></div>
		<div style="float:right;"><a href="examples/map-example.php">Map Example</a></div>

		<br>

		<br><hr><br>

	</body>
</html>
