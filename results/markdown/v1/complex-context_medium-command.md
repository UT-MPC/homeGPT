# complex context, medium command

## Instructions

For every trial in this file, please assign a binary score (0 or 1) based on the following:

- Poor response (0): The changes to the devices do not at all reflect the intent behind the user command, or the response is malformed/garbled.
- Good response (1): The changes to the devices are reasonable for the command. You can imagine _someone_             being satisfied with the result, even if it is somewhat subjective (e.g., based on different personal preferences).

## Trial 0 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
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
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

## Trial 1 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        },
        "lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        }
      },
      "tvs": {
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

## Trial 2 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        },
        "lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        }
      },
      "tvs": {
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

## Trial 3 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        },
        "lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        }
      },
      "tvs": {
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
-         "volume": 20
?                   ^
+         "volume": 30
?                   ^
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
-         "volume": 20
?                   ^
+         "volume": 30
?                   ^
        }
      }
    }
  }
```

## Trial 4 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
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
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

## Trial 5 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        },
        "lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        }
      },
      "tvs": {
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
-         "volume": 20
?                   ^
+         "volume": 50
?                   ^
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
-         "volume": 20
?                   ^
+         "volume": 50
?                   ^
        }
      }
    }
  }
```

## Trial 6 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        },
        "lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        }
      },
      "tvs": {
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

## Trial 7 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        },
        "lamp": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
-           "g": 255,
?                ^^^
+           "g": 0,
?                ^
-           "b": 255
?                ^^^
+           "b": 0
?                ^
          }
        }
      },
      "tvs": {
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

## Trial 8 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
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
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

## Trial 9 - complex context, medium command 

command: **get ready for a party**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
    "bedroom": {
      "lights": {
        "bedside_lamp": {
          "state": "off",
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
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "color": {
            "r": 255,
            "g": 255,
            "b": 255
          }
        },
        "lamp": {
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
        "living_room_tv": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      },
      "speakers": {
        "living_room_speaker": {
-         "state": "off",
?                    ^^
+         "state": "on",
?                    ^
          "volume": 20
        }
      }
    }
  }
```

