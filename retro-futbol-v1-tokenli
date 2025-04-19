
const room = HBInit({
  roomName: "Futsal Gerçekçi Map | Retro Futbol",
  maxPlayers: 12,
  public: true,
  token: "thr1.AAAAAGgD0OGgC5nA4I2ryA.lt8EOkTEfOw"
});

room.onRoomLink = function(link) {
  console.log("🔗 Oda linki:", link);
};

room.onPlayerJoin = function(player) {
  room.sendChat("👋 Hoş geldin, " + player.name + "!");
};

// Basit bir komut örneği:
room.onPlayerChat = function(player, message) {
  if (message === "!komut") {
    room.sendChat("✅ Komut çalıştı!");
  }
};
