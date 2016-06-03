# crypt

This whitepaper describes how the Crypt server and client components combine to provide self-hosted FileVault 2 recovery key escrow for Macs. It was created by Graham Gilbert, and is in active use in many institutions worldwide. Crypt incorporates an enforcement GUI agent and a Django-based web console for escrowing the recovery key, among other secrets. The web component logs access and incorporates an approval workflow, so techs are accountable for retrieving the information, and enables the tracking of other secrets like firmware or local account passwords.