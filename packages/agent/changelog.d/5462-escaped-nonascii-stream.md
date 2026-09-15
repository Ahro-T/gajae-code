### Fixed

- Provisional streaming consumers can reject an escaped-non-ASCII tool-call turn after earlier updates without publishing its terminal message, allowing AgentSession to resample the turn without persisting defective provider metadata.
