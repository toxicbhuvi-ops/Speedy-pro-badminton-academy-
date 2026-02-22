# Speedy-pro-badminton-academy-
Court {
  id: String,
  name: String
}

Slot {
  id: String,
  courtId: String,
  startTime: DateTime,
  endTime: DateTime,
  isBooked: Boolean
}

Booking {
  id: String,
  slotId: String,
  userId: String,
  bookedAt: DateTime
}
