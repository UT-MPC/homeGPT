# simple context, medium command

## Instructions

For every trial in this file, please assign a binary score (0 or 1) based on the following:

- Poor response (0): The changes to the devices do not at all reflect the intent behind the user command, or the response is malformed/garbled.
- Good response (1): The changes to the devices are reasonable for the command. You can imagine _someone_             being satisfied with the result, even if it is somewhat subjective (e.g., based on different personal preferences).

## Trial 0 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 1 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 2 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 3 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 4 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 5 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 6 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 7 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 8 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

## Trial 9 - simple context, medium command 

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
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    },
    "living_room": {
      "lights": {
        "overhead": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        },
        "lamp": {
-         "state": "off"
?                    ^^
+         "state": "on"
?                    ^
        }
      }
    }
  }
```

