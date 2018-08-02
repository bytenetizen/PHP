# PHP
define('ROOT_DIR', $_SERVER['DOCUMENT_ROOT']);

require_once ROOT_DIR . '/libs/db.php';

require_once(realpath('libs/db.php'));

        $time_sql = "AND utro_podcast.stamp BETWEEN " .strtotime('-30 days', time()). " AND " .mktime(0,0,0,date('m'),date('d'),date('Y'));


#############################################################
<form method="post">
  ...
  <input type="submit" name="save" value="Сохранить" />
  <input type="submit" name="delete" value="Удалить" />
</form>
PHP:

if (isset($_POST['save'])) {
  ...
}
else if (isset($_POST['delete'])) {
  ...
}
###################################################

<?php
    print_r($_POST);
    print_r($_GET);
    echo $_SERVER['REQUEST_METHOD'];
?>
###################################################
if ( !R::testConnection() )
{
        exit ('Нет соединения с базой данных');
}



<?php
удаляет все старше 30 дней
$del_date=$time-2592000;    //время в секундах (2592000 сек. = 30 дней)
$res=mysqli_query($db,"DELETE FROM ocenka_comment WHERE date<".$del_date."");
?>



$query = R::getRow("SELECT * FROM pages WHERE pagealias='".$url."' AND pagepublish='Y' LIMIT 1");
R::testConnection();

$today = date("Y-m-d H:i:s");
echo $today;
//2018-07-24 18:12:08
//18:15:59
$todayhors = date("H:i:s");
echo '<br>'. $todayhors;
if ($todayhors >= '18:20:00' && $todayhors <= '18:21:00' ){
    echo '<br>go';
}else{
    echo '<br>no';
}

if ($today >= '2018-07-24 18:24:00' && $today <= '2018-07-24 18:25:00' ){
    echo '<br>go foo';
}else{
    echo '<br>no fo';
}


function myfunction (){
    
    echo '<br>he my function';
}
myfunction ();


https://postovoy.net/54.html
