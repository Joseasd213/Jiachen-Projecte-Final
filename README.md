## Planificació del projecte

```mermaid
gantt
    title Planificación del Proyecto por Sprints
    dateFormat  YYYY-MM-DD
    axisFormat  %d %b

    section 🟢 Sprint 1: Definición
    Ideas principales            :a1, 2023-04-20, 2d
    Lluvia de ideas             :after a1, 2d
    Ilustraciones y prototipos  :after a1, 3d
    Inicio del informe          :a4, 2023-04-22, 10d

    section 🟡 Sprint 2: Desarrollo
    Página web (inicio)         :b1, 2023-05-05, 10d
    Desarrollo Raspberry        :b2, 2023-05-05, 10d
    Continuación del informe    :b3, 2023-05-05, 10d

    section 🔵 Sprint 3: Cierre
    Finalizar página web        :c1, 2023-05-19, 5d
    Finalizar informe           :c2, 2023-05-19, 5d
    Revisión                    :c3, 2023-05-25, 2d
    Feedback docentes           :after c3, 2d
    Refinamiento                :after c3, 2d
    Lanzamiento final           :c6, 2023-05-29, 1d
