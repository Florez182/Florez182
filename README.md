graph TD
    A[Inicio: Monitoreo de procesos] -->|Abogado| B{¿Existe proceso contra TAX INDIVIDUAL S.A.?}
    B -->|No| C[Continuar monitoreo periódico]
    C --> A
    B -->|Sí| D[Notificación de la demanda]
    D -->|Juzgado| E[Recepción de la demanda]
    E -->|Abogado| F[Análisis de la demanda]
    F -->|Abogado| G[Preparar contestación de la demanda]
    G -->|Abogado| H[Presentar contestación de la demanda]
    H -->|Juez| I[Audiencia inicial]
    I -->|Juez/Partes| J[Etapa probatoria]
    J -->|Partes| K[Alegatos de conclusión]
    K -->|Juez| L[Sentencia de primera instancia]
    L -->|Partes| M{¿Se presenta recurso de apelación?}
    M -->|No| N[Ejecutoria de la sentencia]
    M -->|Sí| O[Segunda instancia]
    O -->|Juez superior| P[Sentencia de segunda instancia]
    P --> Q{¿Se presenta recurso de casación?}
    Q -->|No| N
    Q -->|Sí| R[Proceso de casación]
    R -->|Corte Suprema| S[Sentencia de casación]
    S --> N
    N -->|Partes| T[Cumplimiento de la sentencia]
    T --> U[Cierre del proceso]
    U --> V[Fin]

    subgraph Responsabilidades del Abogado de TAX INDIVIDUAL S.A.
        W[Monitorear procesos en la página de la rama judicial]
        X[Analizar la demanda recibida]
        Y[Preparar y presentar contestación de la demanda]
        Z[Recopilar y presentar pruebas de defensa]
        AA[Asistir a audiencias]
        AB[Presentar alegatos de defensa]
        AC[Evaluar y presentar recursos si es necesario]
    end

    subgraph Registros
        AD[Demanda recibida]
        AE[Contestación de la demanda]
        AF[Actas de audiencias]
        AG[Pruebas documentales de defensa]
        AH[Sentencias]
        AI[Recursos presentados]
    end

    subgraph Lineamientos
        AJ[Revisar diariamente la página de la rama judicial]
        AK[Responder dentro de los plazos legales]
        AL[Preparar una defensa sólida y bien documentada]
        AM[Mantener comunicación constante con TAX INDIVIDUAL S.A.]
        AN[Analizar cuidadosamente la viabilidad de recursos]
        AO[Evaluar posibilidades de conciliación]
