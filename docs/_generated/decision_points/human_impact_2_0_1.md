<!-- This content is autogenerated by doctools.py. Do not Edit. -->
!!! note "Human Impact v2.0.1"

    === "Text" 
    
        Human Impact is a combination of Safety and Mission impacts.

        | Value | Definition |
        |:-----|:-----------|
        | Low | Safety Impact:(Negligible) AND Mission Impact:(None OR Degraded OR Crippled) |
        | Medium | (Safety Impact:Negligible AND Mission Impact:MEF Failure) OR (Safety Impact:Marginal AND Mission Impact:(None OR Degraded OR Crippled)) |
        | High | (Safety Impact:Critical AND Mission Impact:(None OR Degraded OR Crippled)) OR (Safety Impact:Marginal AND Mission Impact:MEF Failure) |
        | Very High | Safety Impact:Catastrophic OR Mission Impact:Mission Failure |
        
    === "JSON"
    
        ```json
        {% include "../../../data/json/decision_points/human_impact_2_0_1.json" %}
        ```