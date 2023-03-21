# medium context, ambiguous command

## Instructions

For every trial in this file, please assign a binary score (0 or 1) based on the following:

- Poor response (0): The changes to the devices do not at all reflect the intent behind the user command, or the response is malformed/garbled.
- Good response (1): The changes to the devices are reasonable for the command. You can imagine _someone_             being satisfied with the result, even if it is somewhat subjective (e.g., based on different personal preferences).

## Trial 0 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 1 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 2 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 3 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 4 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 5 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 6 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 7 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 8 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

## Trial 9 - medium context, ambiguous command 

command: **i am tired**

chatgpt's changes to the devices: 

``` json
  {
    "user": {
      "location": "living_room"
    },
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
      }
    }
  }
```

