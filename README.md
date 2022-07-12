# geofencing

        mGeofencePendingIntent =
            PendingIntent.getBroadcast(requireContext(), 0, intent,
                PendingIntent.FLAG_UPDATE_CURRENT or PendingIntent.FLAG_MUTABLE) // PendingIntent.FLAG_MUTABLE
