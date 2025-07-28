# Skaan-Downwash-Velocity

I created this estimation formula for my worldbuilding because i want to make something rather believable for a flying humanoid race.

```
Scaling Factor = 0.5 to 0.8

k = (Wingspan * Wingdepth) / Wing area

Where (Wingspan * Wingdepth) represents perfect wing of 1 or perfect rectangle = B = Bounding box.

Or simply; k = B / Wing area

=== Conventional ===
Effective Radius = Wingspan x 0.6
Downwash Velocity Simplified (Vd = X m/s) = Scaling Factor x 2 x 3.14 x Flap Frequency x Effective Radius x sin(Maximum Wing Angular)

=== Reimagined ===
Skaan Downwash Velocity (Vd = X m/s) = k x 2 x 3.14 x frequency x ( (L1 x sin(angle1) ) + (L2 x (sin(angle1) + sin(angle2) ) )  + (L3 x (sin(angle1) + sin(angle2) + sin(angle3) ) ) )
Breakdown:
Wingspan = L1 + L2 + L3 or possibly L4 and so on.
Adjust accordingly to how many segmentation are there, if there are only two, then skip L3
===

Thrust Force (N) = 2 x Air Density x Wing Area x (Vd)²
Weight (N) = mass x 9.8 m/s²
TWR = Thrust Force / Weight
Vertical Acceleration (m/s²) = Thrust Force / mass
Horizontal Thrust (N) = Thrust Force x cos(Angle of Attack)
Horizontal Acceleration (m/s²) = Horizontal Thrust / mass

Flap Frequency (Hz) = Downwash Velocity / (Scaling Factor × 3.14 × Wingspan × sin(Maximum Wing Angle))

Drag Coefficient of a humanoid leaning 45° frontward:
  T-shirt and Jeans = 0.9
  Naked / Tight-fitting = 0.8
Estimated Frontal Area of human leaning 45° frontward = 0.4m²
Airspeed = Target Airspeed

Lift Force (N) = 0.5 x Wing Coefficient x Air Density x Wing Area x (Target Airpeed)²
Drag Force (N) = 0.5 x Drag Coefficient x Frontal Area x (Airspeed)²
Vsteady (m/s) = sqrt(2 × (Thrust Force - Drag Force - Weight))
```

Skaan here is referring to my original race in my worldbuilding, here is the dossier of Skaan:
```
Race Name: Skaan
Category: Avian Humanoid
Lifespan: ≈8900 years
Alignment: Lawful Good

Physiological Characteristics:

The Skaan are winged humanoid beings characterized by their impressive feathered wings. Fully grown adults typically possess wingspans ranging from 8-12 meters, with variation determined by both genetics and developmental factors. Those who engage in extensive flight during their youth tend to develop longer wings due to centrifugal forces creating beneficial stress on growing bone and muscle tissue.

Wing:
Their wings are feathered wings, and feature a unique skeletal structure that includes several specialized bones:
- Humerus: Capable of rotation similar to human shoulder joints. Skaan wing attached and anchored to their iliac bone.
- Ulnahumeri: Specialized joint connecting to the humerus
- Ulnaradia: Mid-wing bone structure
- Metacarpus/Primaries: Outer wing structure supporting flight feathers

Average Wingspan: ≈8 meters
Average Wing Surface Area: ≈2x2.13m²
Average Height: ≈170cm
Average weight: 70kg

Flying Capability (Avg.):
  Weight: 686 N
  Frontal Area @45°: 2.54m²
  Energy Efficient Flight:
    - Wing Surface Area: 4.26 m²
    - Flap Frequency: 0.7 Hz
    - Downwash Velocity: 14.19 m/s
    - Thrust Force: 2573.33 N
    - Horizontal Force: 1819.62 N
    - Horizontal Acceleration: 27.99 m/s²
    - Drag Force: 792.84 N
    - Speed: 66.24 km/h

This complex joint system allows for remarkable aerial maneuverability without the need for a tail. Wing folding is achieved through a sophisticated arrangement of these joints, allowing wings to compact against the body in a cloak-like configuration when not in flight.

Flight Modes.

The Skaan possess several specialized flight modes enabled by their unique wing structure:

- Hovering: Utilizing their rotational humerus capability, Skaan can maintain stationary flight, particularly useful for precise aerial maneuvers and observation.

- Gliding: With their expansive wingspan, Skaan excel at energy-efficient gliding, allowing them to cover great distances with minimal exertion.

- Power-Takeoff: The rotational capability of the humerus is crucial when launching from ground level without the advantage of height, providing the necessary power for liftoff.

- High-Speed Flight: During rapid flight, the humerus is typically tucked close to the body, becoming passive to reduce drag while the other wing structures maintain aerodynamic efficiency.

- Maneuvering: Without tails, all directional control is managed through their complex wing articulation, similar to how humans might steer while swimming but with greater precision thanks to their specialized joint structure.

This versatile flight system allows Skaan to adapt to various aerial situations without the need for tail stabilization, making them remarkably agile despite their large wingspan.

Flight Capabilities:
Different wing spans correlate with varying flight specializations. Body-to-wing ratio [1:9]
- 8-meter wingspan: Greater maneuverability, rapid direction changes, and aerial acrobatics
- 10-meter wingspan: Balanced flight profile with moderate efficiency and maneuverability
- 12-meter wingspan: Superior gliding efficiency and endurance for long-distance flight

Reproduction and Development:
The Skaan are an exclusively female species. Reproduction occurs through a budding process within the womb, with individuals capable of producing up to five offspring during their reproductive cycle.

Ripe Adult (Reproductive Cycle) (5000-5400 Years):
Period of biological readiness for budding.
Internal processes align for offspring development.
This 400 year period includes the preparation, the budding process, and the recovery.
The actual budding process may only take a small portion of this time.
Due to the large energy requirements.

Social Structure.
Age Classifications:
1. Elder
2. Adult
3. Juvenile

Warrior/Combat Ranks
1. Saint (highest)
2. Elite
3. Surorie ("sisters" - standard rank)

Cultural Characteristics:
The Skaan exhibit a strong maternal instinct that extends beyond biological offspring. Any elder encountering a juvenile Skaan will instinctively assume responsibility for their care and development. This communal child-rearing approach is deeply embedded in their nature and cultural practices.

As embodiments of grace, beauty, and purity, the Skaan fulfill an angel-like role in their world. Their primary weapon is the Glaz, a long-handled bladed weapon similar to a Halberd, which complements their aerial combat capabilities of swoop, dash, and dive attack.

Habitat.
The Skaan share territory with the Ueban, a separate humanoid species specialized for cliff-dwelling and climbing. This shared ecological niche has led to significant interaction between the two species.
```

Ray Vietii 2025
