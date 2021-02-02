# livecoding-beyond-hexagonal-architecture
The code for the live coding session of our Beyond Hexagonal Architecture talk.


## Slides
https://fr.slideshare.net/ThomasPierrain/beyond-hexagonal-architecture

![HexagonalOrNot](./HexagonalOrNot.JPG)

--- 

## HEXAGONAL ARCHITECTURE VERSION

![Hexa-WrapUp](./Hexa-WrapUp.png)

### Acceptance tests (Outside-in diamond style)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/hexagonal/SeatsSuggestions/TheaterSuggestions.Tests/AcceptanceTests/SeatsSuggestionsControllerShould.cs

### The Hexagon (SeatAllocator)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/hexagonal/SeatsSuggestions/SeatsSuggestions.Domain/SeatAllocator.cs

### The left-side port (WebController)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/hexagonal/SeatsSuggestions/SeatsSuggestions.Api/Controllers/SeatsSuggestionsController.cs

---

## FUNCTIONAL CORE VERSION

![Core-WrapUp](./Core-WrapUp.png)

### The Functional core (SeatAllocator)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/functional-core/SeatsSuggestions/SeatsSuggestions.Domain/SeatAllocator.cs


### The Imperative Shell (WebController)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/functional-core/SeatsSuggestions/SeatsSuggestions.Api/Controllers/SeatsSuggestionsController.cs


