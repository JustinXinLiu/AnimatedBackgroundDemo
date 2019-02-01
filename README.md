# AnimatedBackgroundDemo
A UWP sample that blends Gradient with BlendEffect using Composition API.

    var graphicsEffect = new BlendEffect()
    {
        Mode = BlendEffectMode.Screen,
        Foreground = new CompositionEffectSourceParameter("Main"),
        Background = new CompositionEffectSourceParameter("Tint"),
    };
    
[Demo](https://twitter.com/justinxinliu/status/1091398295899914240)
