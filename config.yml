var config = {
    style: 'mapbox://styles/emmaw99/clzgc9k8z001t01pb2klvch5h',
    accessToken: 'pk.eyJ1IjoiZW1tYXc5OSIsImEiOiJjbHpraml5cnEwbndrMnBxMDd1OWJoeGZmIn0.W2JtT0IJEJAfL5D7gJMT-A',
    showMarkers: false,
    markerColor: '#3FB1CE',
    //projection: 'equirectangular',
    //Read more about available projections here
    //https://docs.mapbox.com/mapbox-gl-js/example/projections/
    inset: false,
    theme: 'dark',
    use3dTerrain: false, //set true for enabling 3D maps.
    auto: false,
    title: 'DC Uses Public Bikes to Party',
    subtitle: "Residents of the District of Columbia use the city's bikeshare program every day to travel from point A to B -- and, data shows, to get from point A to the bar.",
    byline: 'By Emmeline Willey',
    footer: 'Source: <a href="https://s3.amazonaws.com/capitalbikeshare-data/index.html" target="_blank">Capital Bikeshare</a> <br> Created using <a href="https://github.com/mapbox/storytelling" target="_blank">Mapbox Storytelling</a> template.',
    chapters: [
        {
            id: 'slug-style-id',
            alignment: 'left',
            hidden: false,
            title: 'District of Day-drinking',
            image: '',
            description: 'The Capital Bikeshare program began in 2008 with just 10 stations. Today it has over 700. District residents use the public bikes every day, but Bikeshare data show that the most trips were taken on days when people hit the town.',
            location: {
                center: [-77.016550, 38.903110],
                zoom: 11,
                pitch: 60,
                bearing: 0
            },
            mapAnimation: 'flyTo',
            rotateAnimation: true,
            callback: '',
            onChapterEnter: [
                // {
                //     layer: 'layer-name',
                //     opacity: 1,
                //     duration: 5000
                // }
            ],
            onChapterExit: [
                // {
                //     layer: 'layer-name',
                //     opacity: 0
                // }
            ]
        },
        {
            id: 'second-identifier',
            alignment: 'right',
            hidden: false,
            title: 'Hotspots',
            image: '',
            description: "June 8th had highest ridership in the first half of 2024 with 24193 trips. Among the ten days with the highest ridership were also the Saturday before St. Patrick's Day, 4/20, and several Fridays and Saturdays in June. Only one of the top ten days was a weekday -- June 12, a Wednesday. <br> Popular stations were clustered around offices, night life strips, and residential areas. There was a particular hub of activity near the NoMa Metro station.",
            location: {
                center: [-77.016550, 38.903110],
                zoom: 12,
                pitch: 60,
                bearing: -43.2,
                // flyTo additional controls-
                // These options control the flight curve, making it move
                // slowly and zoom out almost completely before starting
                // to pan.
                //speed: 2, // make the flying slow
                //curve: 1, // change the speed at which it zooms out
            },
            mapAnimation: 'flyTo',
            rotateAnimation: true,
            callback: '',
            onChapterEnter: [
                {
                 layer: 'popst-628mb0',
                 opacity: 1,
                duration: 5000
                 }
            ],
            onChapterExit: []
        },
        {
            id: 'third-identifier',
            alignment: 'left',
            hidden: false,
            title: 'On the Road',
            image: '',
            description: "Stations along bike routes were among the most frequented. <br> The longest ride was 21 hours and 12 minutes, and the average ride was 10 minutes and 4 seconds. The shortest ride was 10 seconds, which is about enough time to notice that something is wrong with the bike.",
            location: {
                center: [-77.016550, 38.903110],
                zoom: 12.52,
                pitch: 8.01,
                bearing: 0.00
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [
                {
                    layer: 'bicycle-lanes-32hrp3',
                    opacity: 1,
                   duration: 5000
                    },
                {
                    layer: 'bike-trails-dyh3sq',
                    opacity: 1,
                    duration: 5000
                     }  
            ],

            onChapterExit: [{
                layer: 'bike-trails-dyh3sq',
                opacity: 0
                },
                {
                layer: 'bicycle-lanes-32hrp3',
                opacity: 0
                },
                {
                layer: 'popst-628mb0',
                opacity: 0
                }
                ]
        },
        {
            id: 'fourth-chapter',
            alignment: 'fully',
            hidden: false,
            title: 'Seasonal Affectation',
            image: '/Users/emmelinewilley/Desktop/LEDE Project data/kM3gt-monthly-ridership.png',
            description: 'Ridership predictably was lowest in January. January 19 had the fewest trips with 2578 rides.',
            location: {
                center: [-77.016550, 38.903110],
                zoom: 12.52,
                pitch: 8.01,
                bearing: 0.00
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [],
            onChapterExit: []
        },
        {
            id: 'fifth-chapter',
            alignment: 'fully',
            hidden: false,
            title: 'Battery Powered',
            image: '/Users/emmelinewilley/Desktop/LEDE Project data/data/ebikesplitexpanded.png',
            description: 'Riders favored classic bikes over electric bikes, but not by much.',
            location: {
                center: [-77.016550, 38.903110],
                zoom: 12.52,
                pitch: 8.01,
                bearing: 0.00
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [],
            onChapterExit: []
        },
        {
            id: 'fourth-identifier',
            alignment: 'right',
            hidden: false,
            title: 'High Risk',
            image: '',
            description: "Despite DC's bike-friendly streets and programs (or because of them), cyclists still face danger on every ride. All crashes involving a cyclist in 2024 so far are depicted on the map. darker circles signal more severe injuries to the cyclist.",
            location: {
                center: [-77.016550, 38.903110],
                zoom: 12.52,
                pitch: 8.01,
                bearing: 0.00
                // flyTo additional controls-
                // These options control the flight curve, making it move
                // slowly and zoom out almost completely before starting
                // to pan.
                //speed: 2, // make the flying slow
                //curve: 1, // change the speed at which it zooms out
            },
            mapAnimation: 'flyTo',
            rotateAnimation: true,
            callback: '',
            onChapterEnter: [
                {
                 layer: '24-bike-crashes-cgf6op',
                 opacity: 1,
                duration: 5000
                 }
            ],
            onChapterExit: []
        },
    ]
};
