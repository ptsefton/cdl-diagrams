@startuml
skinparam handwritten true
skinparam FontSize 24
skinparam InterfaceFontSize 24

skinparam titleFontSize 42
skinparam arrowFontSize 24
skinparam arro  wColor DarkRed

skinparam arrowThickness 4

skinparam defaultFontName Chalkduster


skinparam activityFontSize 24
skinparam activityFontName Chalkduster
skinparam activityDiamondFontSize 24
skinparam activityArrowFontSize 24

skinparam note  {
    BackgroundColor<< workspace >>  #FFC7D8
    BackgroundColor<< repository >>  springgreen
    BackgroundColor<< guidance >>  yellow
    BackgroundColor<< standards >>  lightblue

    BorderThickness 4
    BackgroundColor transparent
    FontSize 24

}

skinparam actor  {
    BackgroundColor<< workspace >>  #FFC7D8
    BorderColor DarkRed

    BackgroundColor<< repository >>  springgreen


    BackgroundColor<< guidance >>  yellow
    FontColor<< guidance >>  #FFC7D8


    BorderThickness 4
    BackgroundColor transparent
    FontSize 24


}

skinparam rectangle  {
    BackgroundColor<< workspace >>  #FFC7D8


    BackgroundColor<< repository >>  springgreen
       BackgroundColor<< standards >>  lightblue


    BackgroundColor<< guidance >>  yellow


    BorderThickness 4
    BackgroundColor transparent
    FontSize 24


}

skinparam cloud  {
    BackgroundColor<< workspace >>  #FFC7D8
    BackgroundColor<< repository >>  springgreen
    BackgroundColor<< guidance >>  yellow
    BackgroundColor<< standards >>  lightblue

    BorderThickness 4
    BackgroundColor transparent

    FontSize 24

}

skinparam database  {
    BackgroundColor<< workspace >>  #FFC7D8
    BackgroundColor<< repository >>  springgreen
    BackgroundColor<< guidance >>  lightyellow
        BackgroundColor<< standards >>  lightblue

    BorderThickness 4
    BackgroundColor transparent

    FontSize 24
}
@enduml