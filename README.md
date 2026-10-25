# WAITWISE classroom prototype

WAITWISE explores how university students interpret uncertain bus arrivals and decide whether to wait, walk or change routes. The current concept uses a printed QR sign at a bus stop to open a phone interface. It is a classroom prototype; arrival estimates, confidence labels, travel times and passenger requests are simulated.

## Open the prototype

- [Passenger phone view](https://charlottewr.github.io/IDEA9106-WAITWISE/)
- [Facilitator controls and concept comparisons](https://charlottewr.github.io/IDEA9106-WAITWISE/facilitator.html)
- [Printable stop QR sign](https://charlottewr.github.io/IDEA9106-WAITWISE/stop-qr-sign.html)

The QR sign links to the passenger view. If GitHub Pages is not enabled, publish the `main` branch from the repository root under **Settings → Pages**.

## What to test

The passenger view includes an ETA range, a qualitative confidence label about prediction reliability, a simulated passenger request flow and travel option comparisons. The facilitator view contains the classroom scenarios and multiple layouts for comparing ETA, confidence, decision support and the optional waiting guide.

To simulate an arrival update, open the passenger and facilitator views in separate tabs of the **same browser on the same device**. Change the scenario in the facilitator tab, then return to the passenger tab. Scenario changes do not sync across different devices. The displayed previous/current estimate and update time are part of this simulation, not a live transport feed.

The passenger request flow records a selection in this demo only. It does not contact a driver or transport operator, reserve a space or confirm assistance. A deployed service would require an authorised transport data source, operational integration and further evaluation.

The older `WaitWise_Print_Kit.pdf` in this repository belongs to an earlier shared-screen classroom concept. Use `stop-qr-sign.html` for the current QR version.
