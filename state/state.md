# State

## What is state?
State is simply information related to an application that is stored in memory. This is information can be pretty much anything pertaining an application, e.g. the current theme of the application:

```

let theme = "dark";

```

This particular piece of information may change based on a particular event, action, or external information.

```
clicker = (theme) => {
    theme = theme // light
}
```
