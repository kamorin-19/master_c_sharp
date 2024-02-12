# master_c_sharp
競馬管理システムのマスターメンテナンス(C#)

# マテリアルデザインの導入方法
- 参考: https://itport.cloud/?p=20131
- NuGetパッケージ管理でMaterialDesignThemesをインストール
- App.xamlに以下を追加
<ResourceDictionary>
　　<ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="pack://application:,,,/MaterialDesignThemes.Wpf;component/Themes/MaterialDesignTheme.Light.xaml" />
        <ResourceDictionary Source="pack://application:,,,/MaterialDesignThemes.Wpf;component/Themes/MaterialDesignTheme.Defaults.xaml" />
        <ResourceDictionary Source="pack://application:,,,/MaterialDesignColors;component/Themes/Recommended/Primary/MaterialDesignColor.DeepPurple.xaml" />
        <ResourceDictionary Source="pack://application:,,,/MaterialDesignColors;component/Themes/Recommended/Accent/MaterialDesignColor.Lime.xaml" />
    </ResourceDictionary.MergedDictionaries>
</ResourceDictionary>
