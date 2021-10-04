# backup service.

The service is started by a .timer at specific times. The backup script creates a full system backup, using rsync, my preffered tool for file transfers.

The secondary service replicates the data from the first backup set on a secondary drive.

