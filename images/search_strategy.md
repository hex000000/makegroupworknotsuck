@startuml

title Simple Object Diagram

object "APlus Search"
object ERIC_Search
object PSYCINFO_Search
object JSTOR_Search
object Web_of_Science_Search
object Proquest_Search
object Scopus_Search
object Libraries_Australia_Search
object APlus_Excluded
object ERIC_Excluded
object PSYCINFO_Excluded
object JSTOR_Excluded
object Web_of_Science_Excluded
object Proquest_Excluded
object Scopus_Excluded
object Libraries_Australia_Excluded

APlus_Search --|> APlus_Excluded
ERIC_Search --|> ERIC_Excluded
PSYCINFO_Search --|> PSYCINFO_Excluded
JSTOR_Search --|> JSTOR_Excluded
Web_of_Science_Search --|> Web_of_Science_Excluded
Proquest_Search --|> Proquest_Excluded
Scopus_Search --|> Scopus_Excluded
Libraries_Australia_Search --|> Libraries_Australia_Excluded


Germany : Liquor = Jagermeister
France : Liquor = Wine
Spain : Liquor = Wine
USA : Liquor = BudLight
Mexico : Liquor = Taquilla
Russia : Liquor = Vodka
Canada : Liquor = Beer
Japan : Liquor = Sake

@enduml
