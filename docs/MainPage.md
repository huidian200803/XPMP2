XPMP 2
========================

Quick Links:
--

- <a href=annotated.html>Full Class List</a>

- <a href=hierarchy.html>Full Class Hierarchy</a>

- <a href=files.html>File List</a>

Order of Callback Execution per Cycle
--

1. Aircraft::FlightLoopCB(), `xplm_FlightLoop_Phase_BeforeFlightModel`
3. AIControlPlaneCount(), `inIsBefore = 1`
4. AIControlPlaneCount(), `inIsBefore = 0`
5. CPLabelDrawing()
6. AIControlPlaneCount(), `inIsBefore = 1`
7. AIControlPlaneCount(), `inIsBefore = 0`
8. CPLabelDrawing()

Links to outside locations:
--

Original libxplanemp:
- <a href="https://github.com/TwinFan/libxplanemp">TwinFan's libxplanemp fork on GitHub</a>
    - <a href="https://github.com/TwinFan/libxplanemp/wiki">wiki explaining differences to the kuroneko fork</a>
- <a href="https://github.com/kuroneko/libxplanemp">kuroneko's original fork on GitHub</a>
    - <a href="https://github.com/kuroneko/libxplanemp/wiki">kuroneko's wiki</a> including notes on CSL development

Original libxplanemp:
- [TwinFan's libxplanemp fork](https://github.com/TwinFan/libxplanemp) on GitHub
    - [wiki explaining differences to the kuroneko fork](https://github.com/TwinFan/libxplanemp/wiki)
- [kuroneko's fork](https://github.com/kuroneko/libxplanemp) on GitHub, a long-time standard and basis of other important forks
    - [kuroneko's wiki](https://github.com/kuroneko/libxplanemp/wiki) including notes on CSL development
