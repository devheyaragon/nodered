# Use this flow to 'Repair DNS (Tailscale DNS)'.

## The problem/symptoms:
- Aragon Master cannot be updated. 
- The Aragon Master 'About' dialog "The Connection State:", shows red text 'not functioning properly due to a lack of DNS connectivity.'

## Procedure
- Open the "Debug messages" (ctrl-g d)
- Press the blue button "← Press to start"
- Observe the "Debug messages"

If the first debug line shows "backup file exists" and the second debug line shows "nameserver is 100.100.100.100", then your DNS in a incorrect state.
There will be a red dot error indicating that the repair procedure will be executed (the last output)

Reboot Aragon from the Aragon Menu "More | Restart Aragon"
**Do not disconnect the power cable, settings might be lost.**

After restart, the About dialog should show green text "OK, connected".
To avoid the same problem re-occurs, Tailscale needs to be updated
Execute the "6. System update" which is visible after "Show/Hide System update" is clicked.