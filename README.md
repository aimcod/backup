# backup service.

The service is started by a .timer at specific times. The backup script creates a full system backu, using rsync.
The secondary service replicates the data on a secondary drive.

