# floatspace2
Extension of the CKEditor FloatSpace plugin that allows re positioning of the panel.

# Installation
Copy the `floatingspace2` folder to your CK plugins folder.

# Configuration
In you CK editor confifg, set the following 2 properties.

    config.removePlugins = 'floatingspace';
    config.extraPlugins = 'floatingspace2'; 

# Usage
Now, the positional config options for floatingspace will be reloaded each time the editor is shown.

So you dont need to destory and re initialize the CK panel if you change these config options, they will be applied on next render of the editor.

    editor.config.floatSpaceDockedOffsetX = -100;
    editor.config.floatSpaceDockedOffsetTop = 50;
    editor.config.floatSpaceDockedOffsetBottom = 100;


    config.floatSpacePinnedOffsetX = 100;
    config.floatSpacePinnedOffsetY = 50;