"auto";

var h ="com.netease.cloudmusic.activity.PlayerActivity";
waitForActivity(h);
toast("start");

while(true){
	text("01:00").waitFor();
	id("o1").findOne().click();
	sleep(5000);
}
