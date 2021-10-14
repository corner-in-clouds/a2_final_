{
    "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
    "width": 600,
    "height": 600,
    "title": "Car accidents in Victoria by month and light condition",
    "data": {
        "url": "https://raw.githubusercontent.com/corner-in-clouds/Xiaoyun.github.io/main/data/a2indexed.csv"
      },
    "mark":"bar",
    "encoding": {
        "x":{
            "field":"ACCIDENT_DATE",
            "timeUnit":"month",
            "title":"month",
            "type":"nominal"
        },
        "y":{
            "aggregate":"count","field":"OBJECTID", "title":"number of accidents","stack":null
        },
        "color":{
            "field":"LIGHT_CONDITION",
            "scale": {
                "domain": [
                  "Dark No street lights",
                  "Dark Street lights off",
                  "Dark Street lights on",
                  "Dark Street lights unknown",
                  "Day",
                  "Dusk/Dawn",
                  "Unk."
                ],
                "range": [
                  "#dee8be",
                  "#c685a5",
                  "#bacaba",
                  "#7a9d86",
                  "#cbb3aa",
                  "#b2d9d6",
                  "#a8c4d9"
                ]
              }
        },
        "opacity": {"value": 1},
        "tooltip":[
          {"field":"LIGHT_CONDITION","type":"nominal",             "title":"Light condition"}
        ]
    }
    }
  