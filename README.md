&lt;gravatar-profile&gt;
============

##Destructions

Install Bower components
```
bower install
```

Import polyfill
```
<script src="bower_components/webcomponentsjs/webcomponents.js"></script>
```

Import element
```
<link rel="import" href="gravatar-profile/gravatar-profile.html">
```

Use element
```
<gravatar-profile></gravatar-profile>
```

##Attributes

| Attribute  | Description | Options | Example  | Default  |
|---|---|---|---|
| email  | Email of gravatar you want | - | ```<gravatar-profile email="name@domain.com"></gravatar-profile>``` | - |
| width | Width of gravatar image | - | ```<gravatar-profile width="130"></gravatar-profile>``` | 80 |
| round | Make the gravatar image round | - | ```<gravatar-profile round></gravatar-profile>``` | false |
| position | Position of the user info | 'horizontal' or 'vertical' | ```<gravatar-profile position="horizontal"></gravatar-profile>``` | vertical |
