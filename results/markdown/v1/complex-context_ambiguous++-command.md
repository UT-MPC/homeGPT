# complex context, ambiguous++ command

## Instructions

For every trial in this file, please assign a binary score (0 or 1) based on the following:

- Poor response (0): The changes to the devices do not at all reflect the intent behind the user command, or the response is malformed/garbled.
- Good response (1): The changes to the devices are reasonable for the command. You can imagine _someone_             being satisfied with the result, even if it is somewhat subjective (e.g., based on different personal preferences).

## Trial 0 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

## Trial 1 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

## Trial 2 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

## Trial 3 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

## Trial 4 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

## Trial 5 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

## Trial 6 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
-         "volume": 20
?                   -
+         "volume": 0
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
-         "volume": 20
?                   -
+         "volume": 0
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
-         "volume": 20
?                   -
+         "volume": 0
        }
      }
    }
  }
```

## Trial 7 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
-         "volume": 20
?                   -
+         "volume": 0
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
-         "volume": 20
?                   -
+         "volume": 0
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
-         "volume": 20
?                   -
+         "volume": 0
        }
      }
    }
  }
```

## Trial 8 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

## Trial 9 - complex context, ambiguous++ command 

command: **I am tired and I want to sleep**

chatgpt's changes to the devices: 

``` json
  {
    "bedroom": {
      "lights": {
        "bedside_lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "bedroom_tv": {
          "state": "off",
          "volume": 20
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
          "state": "off",
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        }
      },
      "tvs": {
        "living_room_tv": {
          "state": "off",
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
          "state": "off",
          "volume": 20
        }
      }
    }
  }
```

