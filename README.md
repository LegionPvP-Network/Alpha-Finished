# Alpha Anticheat
Alpha is a next generation AntiCheat,
it records suspicous actions and saves them so they can later be reviewed.
Alpha does not interact with the server's performance in any way, it is as smooth as we could make it.

<details>
  <summary>
    Player Tracking.
  </summary>
  <ul>
    <li>Movement Tracker
    <li>Lag Tracker
    <li>Rotation Tracker
    <li>Action Tracker
    <li>Flag Tracker
  </ul>
</details>
<details>
  <summary>
    Replay System Tracking.
  </summary>
  <ul>
    <li>Block placement Tracker
    <li>Block breaking Tracker
    <li>Movement Tracker
    <li>Rotations Tracker
    <li>Action Tracker
    <li>Death Tracker
    <li>Replay max time calculation
    <li>Replay speed increaser
    <li>Replay speed decreaser
    <li>Replay pausing
    <li>Replay unpausing
  </ul>
</details>

## Anticheat Checks

<details>
  <summary>
    Movement.
  </summary>
  <ul>
    <li>Anti Immobile
      <li>Bhop
    <summary>
    Flight
  </summary>
  <ul>
    <li>A - (Check if a user keeps the same Y while in the air).
      <li>B - (Check if a user's Y goes up instead of down).
        <li>C - (Checks if a user is moving too fast while in the air).
    </ul>
    <summary>
    HighJump
  </summary>
  <ul>
    <li>A - (Checks if a user jumps way beyond the jump limit).
      <li>B - (Checks if an user jumps higher then HIS max jump height).
    </ul>
    <li>NoClip
    <summary>
    Speed
  </summary>
  <ul>
    <li>A - (Checks if a user is too fast while sneaking).
      <li>B - (Checks if a user is too fast without using sprint).
        <li>C- (Checks if a user is moving beyond the possible speed).
    </ul>
    <li>Step
    </ul>
  </ul>
</details>
<details>
  <summary>
    Combat.
  </summary>
  <ul>
    <summary>
    Aim Assist
  </summary>
  <ul>
    <li>A - (Checks for snappy rotations).
      <li>[DISABLED] B - (Checks for a weird angle).
        <li>C - (Checks for constant rotation).
          <li>D - (Checks for invalid rotation).
            <li>E - (Checks for impossible rotation).
    </ul>
    <summary>
    Aura
  </summary>
  <ul>
    <li>A - (Checks if an user is hitting multiple targets).
      <li>B - (Checks if a user is target strafing around players).
        <li>C - (Checks for high hit accuracy).
          <li>D - (Checks if an user has their inventory open while attacking).
            <li>E - (Checks if an user has invalid movements while attacking).
              <li>F - (Checks for large head movements without decelerating).
    </ul>
    <li>AutoClicker
      <li>Criticals
        <li>Reach
    </ul>
  </ul>
</details>

<details>
  <summary>
    Miscellaneous.
  </summary>
  <ul>
    <li>EditionFaker
      <li>InventoryMove
    <summary>
    NoSlowDown
  </summary>
  <ul>
    <li>A - (Checks if the player does not slow down while consuming an consumable item).
      <li>B - (Checks if the player does not slow down while walking thru cobweb).
    </ul>
    <summary>
    Packets
  </summary>
  <ul>
    <li>A - (Checks if an user is hitting himself).
      <li>B - (Checks for invalid pitch).
        <li>C - (Checks if a player is sprinting an sneaking at the same time).
          <li>[DISABLED] D - (Checks if a player does not have swing animations).
            <li>E - (Checks if a player is doing invalid movements while swimming).
              <li>[DISABLED] F - (Checks if the user is onground on the server but not on the client side).
                <li>[DISABLED] G - (Check if a user is swimming in air).
                  <li>[DISABLED] G - (Checks if the player is spoofing onGround packets).
    </ul>
    <li>Timer
    </ul>
  </ul>
</details>


**NOTE**: This anticheat is still in development, and has not been released to the public. (might stay private, might sell. not sure)

## License
"Alpha" is under [Apache-2.0 License](https://github.com/LegionPvP-Network/Alpha/blob/master/LICENSE)
