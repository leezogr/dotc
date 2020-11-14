$(document ).ready(function(){
    
    $('#toggle').click(function(){
        $('.dtc-container-full').toggle();
    })

    //날짜//
    
    let weatherIcons = {
        '01d' : 'icons/01d.png',
        '02d' : 'icons/02d.png',
        '03d' : 'icons/03d.png',
        '04d' : 'icons/04d.png',
        '09d' : 'icons/09d.png',
        '10d' : 'icons/10d.png',
        '11d' : 'icons/11d.png',
        '13d' : 'icons/13d.png',
        '50d' : 'icons/50d.png',
        
        '01n' : 'icons/01n.png',
        '02n' : 'icons/02n.png',
        '03n' : 'icons/03n.png',
        '04n' : 'icons/04n.png',
        '09n' : 'icons/09n.png',
        '10n' : 'icons/10n.png',
        '11n' : 'icons/11n.png',
        '13n' : 'icons/13n.png',
        '50n' : 'icons/50n.png',
    }
    let today = new Date();   
    let month = today.getMonth() + 1;  // 월
    let date = today.getDate();  // 날짜
    let day = today.getDay();  // 요일
    let week = new Array('일', '월', '화', '수', '목', '금', '토')

    
    var $date = month + '.' + date + ' ' + week[day] + ''
    
    $('.date').append($date)
    

        $.ajax({     
        url:'https://api.openweathermap.org/data/2.5/onecall?lat=37.5642135&lon=127.0016985&exclude=minutely&appid=ef1c424f6028d4f1109693439a708064&units=metric&lang=kr',
        dataType: 'json',
        type: 'GET',
        success: function(data){
            
            //주간 날씨 요약//
            
            for (var i=1; i<8; i++){
            var d = new Date()
            var week = new Array('일', '월', '화', '수', '목', '금', '토')
            var $weeklyWeather = (data.daily[i].weather[0].description);
            var $weeklyIcon = (data.daily[i].weather[0].icon);
            var $weeklyMin = Math.ceil(data.daily[i].temp.min)  + '°C';
            var $weeklyMax = Math.ceil(data.daily[i].temp.max)  + '°C';

            
            $('.weekly').append('<div class="dot weeklyTemp' + i + '"> </div>'+'<hr class="dots' + i + '">');
            $('.weeklyTemp'+i).append('<span class="weekDays">'+week[(d.getDay()+i)%7] + '요일</span>');
            $('.weeklyTemp'+i).append('<span class="weekIcon"> <img src="' + weatherIcons[$weeklyIcon] + '" width="60">');
            $('.weeklyTemp'+i).children('.weekcon').append('<span class="explain">' + $weeklyWeather +'</span>');
            $('.weeklyTemp'+i).append('<span class="weekTemp">'+'<span class="gray">'+$weeklyMin + '</span>'+ ' &nbsp&nbsp' + $weeklyMax+'</span>');
            
            }
            
            //반응형 날씨 요약//
            
            var $dailyMin = Math.ceil(data.daily[0].temp.min)  + '°C';
            var $dailyMax = Math.ceil(data.daily[0].temp.max)  + '°C';
            var $dailyFeelsMin = Math.ceil(data.daily[0].feels_like.morn)  + '°C';
            var $dailyFeelsMax = Math.ceil(data.daily[0].feels_like.day)  + '°C';
            
            $('.today_minmax').append($dailyMin  + ' / '+ ' '+ $dailyMax +'<br>');
            $('.today_feelsminmax').append($dailyFeelsMin + ' / '+ ' '+ $dailyFeelsMax +'<br>');
            


            
            //일간 날씨//
            for (var i=0; i<24; i++){
                var $hourIcon = (data.hourly[i].weather[0].icon);
                var $hourWeather = (data.hourly[i].weather[0].description);
                var $hourTemp = Math.ceil(data.hourly[i].temp) + '°C';
                var rt = (i+1)*3  
                $('.hourly').append('<div class="hourlyTemp' + i  + '"> </div>');
                $('.hourlyTemp'+i).append('<img src="http://openweathermap.org/img/wn/' + $hourIcon + '@2x.png" width="50">'+'<br>');
                $('.hourlyTemp'+i).prepend($hourTemp+'<br>');                
                $('.hourlyTemp'+i).append($hourWeather+'<br>');
                $('.hourlyTemp'+i).append(i + '시'+'<br>')
            }
            
            
            
            //현재 날씨//
            var $Icon = (data.current.weather[0].icon);
            var $Weather = (data.current.weather[0].description);
            var $Temp = Math.ceil(data.current.temp) + '°C';
            var $min = Math.ceil(data.daily[0].temp.min)  + '°C'
            var $max = Math.ceil(data.daily[0].temp.min)  + '°C'

 
            $('.CurrIcon').append('<img class="todayimage" src="' + weatherIcons[$Icon] + '" width="256">');
            $('.CurrWeather').append($Weather);
            $('.CurrTemp').prepend($Temp);
            $('.minmax').appned($min + '/'+ $max)


        }
    })
});

expireDate = new Date
expireDate.setMonth(expireDate.getMonth()+6)
jcount = eval(cookieVal("jaafarCounter"))
jcount++
document.cookie = "jaafarCounter="+jcount+";expires=" + expireDate.toGMTString()

function cookieVal(cookieName) {
	thisCookie = document.cookie.split("; ")
	for (i=0; i<thisCookie.length; i++){
		if (cookieName == thisCookie[i].split("=")[0]){
			return thisCookie[i].split("=")[1]
		}
	}
	return 0
}

function page_counter(){
	for (y=0;y<(jcount.toString().length);y++)
		document.write('<span class="counter">'+jcount.toString().charAt(y)+'</span>')
}
