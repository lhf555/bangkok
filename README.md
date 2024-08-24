<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_573a6c3d324f628d6dd4e8cf40ede42d {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>
    
    
            <div class="folium-map" id="map_573a6c3d324f628d6dd4e8cf40ede42d" ></div>
        
</body>
<script>
    
    
            var map_573a6c3d324f628d6dd4e8cf40ede42d = L.map(
                "map_573a6c3d324f628d6dd4e8cf40ede42d",
                {
                    center: [13.7563, 100.5018],
                    crs: L.CRS.EPSG3857,
                    zoom: 12,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_c19aa38fd551faf2d43a46dbdb51f6dd = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var marker_299a7af57cc601ec42dd14f641e03c95 = L.marker(
                [13.7379, 100.5583],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_722bca5ac3fbefbdb1137704cde60b00 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_299a7af57cc601ec42dd14f641e03c95.setIcon(icon_722bca5ac3fbefbdb1137704cde60b00);
        
    
        var popup_054da095442265e160f9235c5d6031ae = L.popup({"maxWidth": "100%"});

        
            var html_710c759fd7ee188bb3acbe2197a0b231 = $(`<div id="html_710c759fd7ee188bb3acbe2197a0b231" style="width: 100.0%; height: 100.0%;">Sukhumvit</div>`)[0];
            popup_054da095442265e160f9235c5d6031ae.setContent(html_710c759fd7ee188bb3acbe2197a0b231);
        

        marker_299a7af57cc601ec42dd14f641e03c95.bindPopup(popup_054da095442265e160f9235c5d6031ae)
        ;

        
    
    
            var marker_11766d476e7759b5db4fe0e87ad019b7 = L.marker(
                [13.7301, 100.5327],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_237d173072f9b38951a45ccbe0f3f407 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_11766d476e7759b5db4fe0e87ad019b7.setIcon(icon_237d173072f9b38951a45ccbe0f3f407);
        
    
        var popup_4155fb24db08c076c170476ab369922d = L.popup({"maxWidth": "100%"});

        
            var html_9bbfa45bb8d79226763407e45bf9b1a4 = $(`<div id="html_9bbfa45bb8d79226763407e45bf9b1a4" style="width: 100.0%; height: 100.0%;">Silom</div>`)[0];
            popup_4155fb24db08c076c170476ab369922d.setContent(html_9bbfa45bb8d79226763407e45bf9b1a4);
        

        marker_11766d476e7759b5db4fe0e87ad019b7.bindPopup(popup_4155fb24db08c076c170476ab369922d)
        ;

        
    
    
            var marker_17c40ec6d8409a73f847a1f68b20c3dd = L.marker(
                [13.7597, 100.4976],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_7c323948ff03d074717b0e9a807c8c12 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_17c40ec6d8409a73f847a1f68b20c3dd.setIcon(icon_7c323948ff03d074717b0e9a807c8c12);
        
    
        var popup_ebec7bc0dc536d47b348be51291609b5 = L.popup({"maxWidth": "100%"});

        
            var html_64336ca5c3c765090402c70a91c263b0 = $(`<div id="html_64336ca5c3c765090402c70a91c263b0" style="width: 100.0%; height: 100.0%;">Khao San Road</div>`)[0];
            popup_ebec7bc0dc536d47b348be51291609b5.setContent(html_64336ca5c3c765090402c70a91c263b0);
        

        marker_17c40ec6d8409a73f847a1f68b20c3dd.bindPopup(popup_ebec7bc0dc536d47b348be51291609b5)
        ;

        
    
    
            var marker_248730597d5dc34a94553ef93f3f04bb = L.marker(
                [13.7261, 100.5108],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_d36fe10198278ffb7d880481e4a01aba = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_248730597d5dc34a94553ef93f3f04bb.setIcon(icon_d36fe10198278ffb7d880481e4a01aba);
        
    
        var popup_0fa291fe8b0a606ebb12379a73c02cd1 = L.popup({"maxWidth": "100%"});

        
            var html_d9d1a6ca0fe785bdae77abe5674f0518 = $(`<div id="html_d9d1a6ca0fe785bdae77abe5674f0518" style="width: 100.0%; height: 100.0%;">Riverside</div>`)[0];
            popup_0fa291fe8b0a606ebb12379a73c02cd1.setContent(html_d9d1a6ca0fe785bdae77abe5674f0518);
        

        marker_248730597d5dc34a94553ef93f3f04bb.bindPopup(popup_0fa291fe8b0a606ebb12379a73c02cd1)
        ;

        
    
    
            var marker_bc602e954f3a248b2b43ec04fdfef0e1 = L.marker(
                [13.7425, 100.5076],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_3812b4b1b95baca36d4baf2c444d0275 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_bc602e954f3a248b2b43ec04fdfef0e1.setIcon(icon_3812b4b1b95baca36d4baf2c444d0275);
        
    
        var popup_cdd2b062ba47635b40bd06d7ee45de85 = L.popup({"maxWidth": "100%"});

        
            var html_8bb0a3e069fab0bd146931defaad70b3 = $(`<div id="html_8bb0a3e069fab0bd146931defaad70b3" style="width: 100.0%; height: 100.0%;">Chinatown</div>`)[0];
            popup_cdd2b062ba47635b40bd06d7ee45de85.setContent(html_8bb0a3e069fab0bd146931defaad70b3);
        

        marker_bc602e954f3a248b2b43ec04fdfef0e1.bindPopup(popup_cdd2b062ba47635b40bd06d7ee45de85)
        ;

        
    
    
            var marker_29bdc4a0d0a8d1d26f933ec68fb0f608 = L.marker(
                [13.69, 100.7501],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_29203c82ffdeac23aac91e4e1e1f4313 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "plane", "iconColor": "white", "markerColor": "black", "prefix": "glyphicon"}
            );
            marker_29bdc4a0d0a8d1d26f933ec68fb0f608.setIcon(icon_29203c82ffdeac23aac91e4e1e1f4313);
        
    
        var popup_2ad0bd705c01d73f4b4b7094363193ad = L.popup({"maxWidth": "100%"});

        
            var html_476968bbd8c847b3c5ec6df1000c421a = $(`<div id="html_476968bbd8c847b3c5ec6df1000c421a" style="width: 100.0%; height: 100.0%;">Aéroport Suvarnabhumi (BKK)</div>`)[0];
            popup_2ad0bd705c01d73f4b4b7094363193ad.setContent(html_476968bbd8c847b3c5ec6df1000c421a);
        

        marker_29bdc4a0d0a8d1d26f933ec68fb0f608.bindPopup(popup_2ad0bd705c01d73f4b4b7094363193ad)
        ;

        
    
    
            var marker_94b87b23a52b6ecd1e8a8a3473bed5b2 = L.marker(
                [13.738, 100.5162],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_3681575d5673506ebb5f6ab819c98126 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "train", "iconColor": "white", "markerColor": "black", "prefix": "glyphicon"}
            );
            marker_94b87b23a52b6ecd1e8a8a3473bed5b2.setIcon(icon_3681575d5673506ebb5f6ab819c98126);
        
    
        var popup_fd0b5910cca7031da553ec474ba9ae97 = L.popup({"maxWidth": "100%"});

        
            var html_3fa5b5f2f54d047ad2b1d5063bc6e757 = $(`<div id="html_3fa5b5f2f54d047ad2b1d5063bc6e757" style="width: 100.0%; height: 100.0%;">Gare de Bangkok (Hua Lamphong)</div>`)[0];
            popup_fd0b5910cca7031da553ec474ba9ae97.setContent(html_3fa5b5f2f54d047ad2b1d5063bc6e757);
        

        marker_94b87b23a52b6ecd1e8a8a3473bed5b2.bindPopup(popup_fd0b5910cca7031da553ec474ba9ae97)
        ;

        
    
    
            var marker_8c516f9005dba224ef582d388e7a5821 = L.marker(
                [13.7516, 100.4923],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_a75e797838355c8d98f8143b599c1625 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "star", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8c516f9005dba224ef582d388e7a5821.setIcon(icon_a75e797838355c8d98f8143b599c1625);
        
    
        var popup_d2ca29c7f85a11dcd52893ab5d17d014 = L.popup({"maxWidth": "100%"});

        
            var html_2c9c12b52e522af0e472bbe9dad25284 = $(`<div id="html_2c9c12b52e522af0e472bbe9dad25284" style="width: 100.0%; height: 100.0%;">Grand Palais</div>`)[0];
            popup_d2ca29c7f85a11dcd52893ab5d17d014.setContent(html_2c9c12b52e522af0e472bbe9dad25284);
        

        marker_8c516f9005dba224ef582d388e7a5821.bindPopup(popup_d2ca29c7f85a11dcd52893ab5d17d014)
        ;

        
    
    
            var marker_db57d24f104fe7e6d65045da1b9783a1 = L.marker(
                [13.7437, 100.4885],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_7078893a473bda144a60b9a331f4e05f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "star", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_db57d24f104fe7e6d65045da1b9783a1.setIcon(icon_7078893a473bda144a60b9a331f4e05f);
        
    
        var popup_af764c69562978645a88d11c6890a465 = L.popup({"maxWidth": "100%"});

        
            var html_fc022e2d4350f8914b082c810ee26606 = $(`<div id="html_fc022e2d4350f8914b082c810ee26606" style="width: 100.0%; height: 100.0%;">Wat Arun</div>`)[0];
            popup_af764c69562978645a88d11c6890a465.setContent(html_fc022e2d4350f8914b082c810ee26606);
        

        marker_db57d24f104fe7e6d65045da1b9783a1.bindPopup(popup_af764c69562978645a88d11c6890a465)
        ;

        
    
    
            var marker_27c44f7baf56b0c52da970fc70a936a2 = L.marker(
                [13.7466, 100.493],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_0cf6b0a4dd96dfa793d44427356b6eeb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "star", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_27c44f7baf56b0c52da970fc70a936a2.setIcon(icon_0cf6b0a4dd96dfa793d44427356b6eeb);
        
    
        var popup_7b4af0785ca18de79c1f71e8ea063f7b = L.popup({"maxWidth": "100%"});

        
            var html_d5e6880ff99812429bb0f7fd214f7d48 = $(`<div id="html_d5e6880ff99812429bb0f7fd214f7d48" style="width: 100.0%; height: 100.0%;">Wat Pho</div>`)[0];
            popup_7b4af0785ca18de79c1f71e8ea063f7b.setContent(html_d5e6880ff99812429bb0f7fd214f7d48);
        

        marker_27c44f7baf56b0c52da970fc70a936a2.bindPopup(popup_7b4af0785ca18de79c1f71e8ea063f7b)
        ;

        
    
    
            var marker_54b3167e237fc08b18d3ada7da38cea8 = L.marker(
                [13.7997, 100.55],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_75d116b11919a742dfa9feb62786bf44 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "star", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_54b3167e237fc08b18d3ada7da38cea8.setIcon(icon_75d116b11919a742dfa9feb62786bf44);
        
    
        var popup_ac1a009395d1ede1043a3c418305113a = L.popup({"maxWidth": "100%"});

        
            var html_b2f01bb0d3fcd4608fba5cdc12fd2e6c = $(`<div id="html_b2f01bb0d3fcd4608fba5cdc12fd2e6c" style="width: 100.0%; height: 100.0%;">Marché de Chatuchak</div>`)[0];
            popup_ac1a009395d1ede1043a3c418305113a.setContent(html_b2f01bb0d3fcd4608fba5cdc12fd2e6c);
        

        marker_54b3167e237fc08b18d3ada7da38cea8.bindPopup(popup_ac1a009395d1ede1043a3c418305113a)
        ;

        
    
    
            var marker_09d00a971c266bf195108526aac695ce = L.marker(
                [13.7533, 100.5093],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_fe76b41949868d92c4f7406c1827abe3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "markerColor": "darkgreen", "prefix": "glyphicon"}
            );
            marker_09d00a971c266bf195108526aac695ce.setIcon(icon_fe76b41949868d92c4f7406c1827abe3);
        
    
        var popup_b2ff2ddb8aff14e0f9ec7a0e87ae40b5 = L.popup({"maxWidth": "100%"});

        
            var html_9fa21c28560e6b6187abcff4b1889c7a = $(`<div id="html_9fa21c28560e6b6187abcff4b1889c7a" style="width: 100.0%; height: 100.0%;">Jay Fai</div>`)[0];
            popup_b2ff2ddb8aff14e0f9ec7a0e87ae40b5.setContent(html_9fa21c28560e6b6187abcff4b1889c7a);
        

        marker_09d00a971c266bf195108526aac695ce.bindPopup(popup_b2ff2ddb8aff14e0f9ec7a0e87ae40b5)
        ;

        
    
    
            var marker_2293563d5c00d7039335d77cdab9dc04 = L.marker(
                [13.7224, 100.5323],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_5be6749547be55db82237702c9812541 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "markerColor": "darkgreen", "prefix": "glyphicon"}
            );
            marker_2293563d5c00d7039335d77cdab9dc04.setIcon(icon_5be6749547be55db82237702c9812541);
        
    
        var popup_8a000d0c43f1c7bc9cac7a59a7e963f0 = L.popup({"maxWidth": "100%"});

        
            var html_8901514f611dc0d96d9ded24d5b52fa7 = $(`<div id="html_8901514f611dc0d96d9ded24d5b52fa7" style="width: 100.0%; height: 100.0%;">Nahm</div>`)[0];
            popup_8a000d0c43f1c7bc9cac7a59a7e963f0.setContent(html_8901514f611dc0d96d9ded24d5b52fa7);
        

        marker_2293563d5c00d7039335d77cdab9dc04.bindPopup(popup_8a000d0c43f1c7bc9cac7a59a7e963f0)
        ;

        
    
    
            var marker_e1e6b8e5210c32744df458f0783160f4 = L.marker(
                [13.7373, 100.5453],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_6256b63fa2df9e929b165b27fcfe0592 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "markerColor": "darkgreen", "prefix": "glyphicon"}
            );
            marker_e1e6b8e5210c32744df458f0783160f4.setIcon(icon_6256b63fa2df9e929b165b27fcfe0592);
        
    
        var popup_957608665dbc73819dc5fbd6e3cc7b22 = L.popup({"maxWidth": "100%"});

        
            var html_62446acebb247d21056657510dc5992a = $(`<div id="html_62446acebb247d21056657510dc5992a" style="width: 100.0%; height: 100.0%;">Gaggan Anand</div>`)[0];
            popup_957608665dbc73819dc5fbd6e3cc7b22.setContent(html_62446acebb247d21056657510dc5992a);
        

        marker_e1e6b8e5210c32744df458f0783160f4.bindPopup(popup_957608665dbc73819dc5fbd6e3cc7b22)
        ;

        
    
    
            var marker_ad66b4a17858aab2f95bc94ac74cf524 = L.marker(
                [13.7233, 100.528],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_30401cc27c5e757bd1a4df3c1fd2a6c3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "darkblue", "prefix": "glyphicon"}
            );
            marker_ad66b4a17858aab2f95bc94ac74cf524.setIcon(icon_30401cc27c5e757bd1a4df3c1fd2a6c3);
        
    
        var popup_3732ec73773987b9522f8bb7b924eb76 = L.popup({"maxWidth": "100%"});

        
            var html_66c1fe2fc430675875be093e05fd6738 = $(`<div id="html_66c1fe2fc430675875be093e05fd6738" style="width: 100.0%; height: 100.0%;">Mahanakhon Tower</div>`)[0];
            popup_3732ec73773987b9522f8bb7b924eb76.setContent(html_66c1fe2fc430675875be093e05fd6738);
        

        marker_ad66b4a17858aab2f95bc94ac74cf524.bindPopup(popup_3732ec73773987b9522f8bb7b924eb76)
        ;

        
    
    
            var marker_cb5ed3304d4d7987c87d322963b2a3fd = L.marker(
                [13.7301, 100.5415],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_802820073f2c5d97d6230e803e19486b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "darkblue", "prefix": "glyphicon"}
            );
            marker_cb5ed3304d4d7987c87d322963b2a3fd.setIcon(icon_802820073f2c5d97d6230e803e19486b);
        
    
        var popup_fd1754d9e162ec7186fc4332d54d0565 = L.popup({"maxWidth": "100%"});

        
            var html_c1f33aef117fbc5e31533cd8851ffed6 = $(`<div id="html_c1f33aef117fbc5e31533cd8851ffed6" style="width: 100.0%; height: 100.0%;">Lumphini Park</div>`)[0];
            popup_fd1754d9e162ec7186fc4332d54d0565.setContent(html_c1f33aef117fbc5e31533cd8851ffed6);
        

        marker_cb5ed3304d4d7987c87d322963b2a3fd.bindPopup(popup_fd1754d9e162ec7186fc4332d54d0565)
        ;

        
    
    
            var marker_a5326d9860b2783d03f5e5e64ac16f34 = L.marker(
                [13.7517, 100.5286],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_260859122c83699536d921f2958d0384 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "darkblue", "prefix": "glyphicon"}
            );
            marker_a5326d9860b2783d03f5e5e64ac16f34.setIcon(icon_260859122c83699536d921f2958d0384);
        
    
        var popup_314b871c052326e5c3233abde1995376 = L.popup({"maxWidth": "100%"});

        
            var html_a05ceff33972db59020737c7acab3704 = $(`<div id="html_a05ceff33972db59020737c7acab3704" style="width: 100.0%; height: 100.0%;">Maison de Jim Thompson</div>`)[0];
            popup_314b871c052326e5c3233abde1995376.setContent(html_a05ceff33972db59020737c7acab3704);
        

        marker_a5326d9860b2783d03f5e5e64ac16f34.bindPopup(popup_314b871c052326e5c3233abde1995376)
        ;

        
    
    
            var marker_8dcbf82dbcd88623b55fcfff4a6e95b4 = L.marker(
                [13.7375, 100.5602],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_9f8caef72cb66cd9151dca3cdb1d93a3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "darkblue", "prefix": "glyphicon"}
            );
            marker_8dcbf82dbcd88623b55fcfff4a6e95b4.setIcon(icon_9f8caef72cb66cd9151dca3cdb1d93a3);
        
    
        var popup_882ac39d7361402fc713e9f914a66670 = L.popup({"maxWidth": "100%"});

        
            var html_77e9a0192f495ec10e3dbe1309d3e6f7 = $(`<div id="html_77e9a0192f495ec10e3dbe1309d3e6f7" style="width: 100.0%; height: 100.0%;">Terminal 21 Shopping Mall</div>`)[0];
            popup_882ac39d7361402fc713e9f914a66670.setContent(html_77e9a0192f495ec10e3dbe1309d3e6f7);
        

        marker_8dcbf82dbcd88623b55fcfff4a6e95b4.bindPopup(popup_882ac39d7361402fc713e9f914a66670)
        ;

        
    
    
            var marker_b1e1f3b850abc8c86349d60098c3ee92 = L.marker(
                [13.7462, 100.53],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_041f1e9e025b75f40167eaecbbb07549 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "darkblue", "prefix": "glyphicon"}
            );
            marker_b1e1f3b850abc8c86349d60098c3ee92.setIcon(icon_041f1e9e025b75f40167eaecbbb07549);
        
    
        var popup_1f15989d09a1e573be1731e267a37e0e = L.popup({"maxWidth": "100%"});

        
            var html_e99a47a18ab97c347ddf4fe8c9245c76 = $(`<div id="html_e99a47a18ab97c347ddf4fe8c9245c76" style="width: 100.0%; height: 100.0%;">MBK Center</div>`)[0];
            popup_1f15989d09a1e573be1731e267a37e0e.setContent(html_e99a47a18ab97c347ddf4fe8c9245c76);
        

        marker_b1e1f3b850abc8c86349d60098c3ee92.bindPopup(popup_1f15989d09a1e573be1731e267a37e0e)
        ;

        
    
    
            var marker_aa40a68c85204273c3d357c7ab3d5900 = L.marker(
                [13.7058, 100.5039],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_776086f6dae14ce622d8b9724a40a9d4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "darkblue", "prefix": "glyphicon"}
            );
            marker_aa40a68c85204273c3d357c7ab3d5900.setIcon(icon_776086f6dae14ce622d8b9724a40a9d4);
        
    
        var popup_344bfbb9b544cb98d2a94031f1021cc0 = L.popup({"maxWidth": "100%"});

        
            var html_9320d55a71fd032a6ffecf8bd810ace9 = $(`<div id="html_9320d55a71fd032a6ffecf8bd810ace9" style="width: 100.0%; height: 100.0%;">Asiatique The Riverfront</div>`)[0];
            popup_344bfbb9b544cb98d2a94031f1021cc0.setContent(html_9320d55a71fd032a6ffecf8bd810ace9);
        

        marker_aa40a68c85204273c3d357c7ab3d5900.bindPopup(popup_344bfbb9b544cb98d2a94031f1021cc0)
        ;

        
    
    
            var marker_2da8ad7830ca8da67119e247c2cb7150 = L.marker(
                [13.8038, 100.5535],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_db35b7b26d8a07cd262cc2b7406659d8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "subway", "iconColor": "white", "markerColor": "lightblue", "prefix": "glyphicon"}
            );
            marker_2da8ad7830ca8da67119e247c2cb7150.setIcon(icon_db35b7b26d8a07cd262cc2b7406659d8);
        
    
        var popup_ad84c1f9e911e5307cae7558080740ed = L.popup({"maxWidth": "100%"});

        
            var html_e3a9e5bc4115d5497af7bf65eaf0704e = $(`<div id="html_e3a9e5bc4115d5497af7bf65eaf0704e" style="width: 100.0%; height: 100.0%;">Mo Chit (BTS)</div>`)[0];
            popup_ad84c1f9e911e5307cae7558080740ed.setContent(html_e3a9e5bc4115d5497af7bf65eaf0704e);
        

        marker_2da8ad7830ca8da67119e247c2cb7150.bindPopup(popup_ad84c1f9e911e5307cae7558080740ed)
        ;

        
    
    
            var marker_d8b3241abe852c76f8423ec9fe50a5a0 = L.marker(
                [13.7466, 100.5346],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_9bf6726f4f3fbf2b6d6b0fe497e5f7fb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "subway", "iconColor": "white", "markerColor": "lightblue", "prefix": "glyphicon"}
            );
            marker_d8b3241abe852c76f8423ec9fe50a5a0.setIcon(icon_9bf6726f4f3fbf2b6d6b0fe497e5f7fb);
        
    
        var popup_51b1da69f75e6c3873a2479706744fa6 = L.popup({"maxWidth": "100%"});

        
            var html_0b05edcea4a8bd0c4ac5ce95b58e0c52 = $(`<div id="html_0b05edcea4a8bd0c4ac5ce95b58e0c52" style="width: 100.0%; height: 100.0%;">Siam (BTS)</div>`)[0];
            popup_51b1da69f75e6c3873a2479706744fa6.setContent(html_0b05edcea4a8bd0c4ac5ce95b58e0c52);
        

        marker_d8b3241abe852c76f8423ec9fe50a5a0.bindPopup(popup_51b1da69f75e6c3873a2479706744fa6)
        ;

        
    
    
            var marker_1e7e6baa83981ab9a07b44dc7da046a4 = L.marker(
                [13.7361, 100.5305],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_e2f7743de92905a4f0f74e76ec484a37 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "subway", "iconColor": "white", "markerColor": "lightblue", "prefix": "glyphicon"}
            );
            marker_1e7e6baa83981ab9a07b44dc7da046a4.setIcon(icon_e2f7743de92905a4f0f74e76ec484a37);
        
    
        var popup_77616dee7925684d53c32a8338a68508 = L.popup({"maxWidth": "100%"});

        
            var html_0806a39601a54e9681b38ba3e4755317 = $(`<div id="html_0806a39601a54e9681b38ba3e4755317" style="width: 100.0%; height: 100.0%;">Asok (BTS)</div>`)[0];
            popup_77616dee7925684d53c32a8338a68508.setContent(html_0806a39601a54e9681b38ba3e4755317);
        

        marker_1e7e6baa83981ab9a07b44dc7da046a4.bindPopup(popup_77616dee7925684d53c32a8338a68508)
        ;

        
    
    
            var marker_bc50ec3533dbbe9c3f9f9205af2b70d8 = L.marker(
                [13.7183, 100.5146],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_1fc0521d5c64664c44df9d921b1c965e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "subway", "iconColor": "white", "markerColor": "lightblue", "prefix": "glyphicon"}
            );
            marker_bc50ec3533dbbe9c3f9f9205af2b70d8.setIcon(icon_1fc0521d5c64664c44df9d921b1c965e);
        
    
        var popup_e11032f7c15a11f1f4decd00a157ee27 = L.popup({"maxWidth": "100%"});

        
            var html_20bf58cee6713918ec8a271d5c6de623 = $(`<div id="html_20bf58cee6713918ec8a271d5c6de623" style="width: 100.0%; height: 100.0%;">Saphan Taksin (BTS)</div>`)[0];
            popup_e11032f7c15a11f1f4decd00a157ee27.setContent(html_20bf58cee6713918ec8a271d5c6de623);
        

        marker_bc50ec3533dbbe9c3f9f9205af2b70d8.bindPopup(popup_e11032f7c15a11f1f4decd00a157ee27)
        ;

        
    
    
            var marker_63956bdf04e64f660661ab88317d8419 = L.marker(
                [13.7566, 100.5323],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_6f9c0449c7101d8348e03143eec58564 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "subway", "iconColor": "white", "markerColor": "lightblue", "prefix": "glyphicon"}
            );
            marker_63956bdf04e64f660661ab88317d8419.setIcon(icon_6f9c0449c7101d8348e03143eec58564);
        
    
        var popup_a9c9f8df9cce066628f52792c59d220f = L.popup({"maxWidth": "100%"});

        
            var html_7705a4aca99309b497d7146bd2082907 = $(`<div id="html_7705a4aca99309b497d7146bd2082907" style="width: 100.0%; height: 100.0%;">Phaya Thai (BTS)</div>`)[0];
            popup_a9c9f8df9cce066628f52792c59d220f.setContent(html_7705a4aca99309b497d7146bd2082907);
        

        marker_63956bdf04e64f660661ab88317d8419.bindPopup(popup_a9c9f8df9cce066628f52792c59d220f)
        ;

        
    
    
            var marker_6c572b025fb74c970aab7070a77f488c = L.marker(
                [13.7385, 100.5574],
                {}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
            var icon_7c609b514d7dbaecf6d779d82f63189e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "subway", "iconColor": "white", "markerColor": "lightblue", "prefix": "glyphicon"}
            );
            marker_6c572b025fb74c970aab7070a77f488c.setIcon(icon_7c609b514d7dbaecf6d779d82f63189e);
        
    
        var popup_e5cb783a538ccc61af47ec4c418ad4f3 = L.popup({"maxWidth": "100%"});

        
            var html_9d20afc8b30fbc93c8e30210285548d3 = $(`<div id="html_9d20afc8b30fbc93c8e30210285548d3" style="width: 100.0%; height: 100.0%;">Nana (BTS)</div>`)[0];
            popup_e5cb783a538ccc61af47ec4c418ad4f3.setContent(html_9d20afc8b30fbc93c8e30210285548d3);
        

        marker_6c572b025fb74c970aab7070a77f488c.bindPopup(popup_e5cb783a538ccc61af47ec4c418ad4f3)
        ;

        
    
    
            var circle_1a21026a3b64f6d9f475b6aa3a7c02d2 = L.circle(
                [13.7379, 100.5583],
                {"bubblingMouseEvents": true, "color": "blue", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "blue", "fillOpacity": 0.4, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1500, "stroke": true, "weight": 3}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
        var popup_c6ec99875b8ad295591f9945f03de3a8 = L.popup({"maxWidth": "100%"});

        
            var html_97be357f2d34901c9e38b56586d41785 = $(`<div id="html_97be357f2d34901c9e38b56586d41785" style="width: 100.0%; height: 100.0%;">Zone recommandée pour les hommes célibataires : Vie nocturne active et variété de restaurants.</div>`)[0];
            popup_c6ec99875b8ad295591f9945f03de3a8.setContent(html_97be357f2d34901c9e38b56586d41785);
        

        circle_1a21026a3b64f6d9f475b6aa3a7c02d2.bindPopup(popup_c6ec99875b8ad295591f9945f03de3a8)
        ;

        
    
    
            var circle_913880efb70ce55e224816b3df62e1ea = L.circle(
                [13.7261, 100.5108],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.4, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1500, "stroke": true, "weight": 3}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
        var popup_a6b62e4625a60c597258c3155859552d = L.popup({"maxWidth": "100%"});

        
            var html_da58173a10c9462e63ac83ea3916df20 = $(`<div id="html_da58173a10c9462e63ac83ea3916df20" style="width: 100.0%; height: 100.0%;">Zone recommandée pour les familles : Calme, proche des attractions culturelles.</div>`)[0];
            popup_a6b62e4625a60c597258c3155859552d.setContent(html_da58173a10c9462e63ac83ea3916df20);
        

        circle_913880efb70ce55e224816b3df62e1ea.bindPopup(popup_a6b62e4625a60c597258c3155859552d)
        ;

        
    
    
            var circle_7f2fef2e83563dbc1f468bcc711a6470 = L.circle(
                [13.7301, 100.5327],
                {"bubblingMouseEvents": true, "color": "purple", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "purple", "fillOpacity": 0.4, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1500, "stroke": true, "weight": 3}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
        var popup_c67b8d1742fafe544b08f0b1d1aab49a = L.popup({"maxWidth": "100%"});

        
            var html_60c0e42ddee7d8a9e2506ab343a8c641 = $(`<div id="html_60c0e42ddee7d8a9e2506ab343a8c641" style="width: 100.0%; height: 100.0%;">Zone recommandée pour les couples : Mélange de détente et d'affaires, proche de Lumphini Park.</div>`)[0];
            popup_c67b8d1742fafe544b08f0b1d1aab49a.setContent(html_60c0e42ddee7d8a9e2506ab343a8c641);
        

        circle_7f2fef2e83563dbc1f468bcc711a6470.bindPopup(popup_c67b8d1742fafe544b08f0b1d1aab49a)
        ;

        
    
    
            var circle_7bb5db1334fd6947b982ae8ac6c8d6c7 = L.circle(
                [13.7597, 100.4976],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.4, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1000, "stroke": true, "weight": 3}
            ).addTo(map_573a6c3d324f628d6dd4e8cf40ede42d);
        
    
        var popup_e32997b742d2b7ca59c4a6dbc1daceb1 = L.popup({"maxWidth": "100%"});

        
            var html_c91024756f6273419eb7c65bf5c31784 = $(`<div id="html_c91024756f6273419eb7c65bf5c31784" style="width: 100.0%; height: 100.0%;">Zone recommandée pour les backpackers : Auberges à prix abordables et ambiance sociale.</div>`)[0];
            popup_e32997b742d2b7ca59c4a6dbc1daceb1.setContent(html_c91024756f6273419eb7c65bf5c31784);
        

        circle_7bb5db1334fd6947b982ae8ac6c8d6c7.bindPopup(popup_e32997b742d2b7ca59c4a6dbc1daceb1)
        ;

        
    
</script>
</html>
