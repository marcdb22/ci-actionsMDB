# 🚀 Marc Durán — Developer Profile

Actualmente cursando 2º de **Desarrollo de Aplicaciones Web (DAW)**. Apasionado por el desarrollo backend, la optimización de código y los sistemas de Integración Continua (CI/CD).

---

## 🛠️ Tecnologías y Herramientas

| Backend | Frontend | DevOps & Herramientas |
| :--- | :--- | :--- |
| PHP 8.x | HTML5 / CSS3 | GitHub Actions 🚀 |
| Java | JavaScript (ES6+) | Git / GitHub |
| MySQL | Markdown | VS Code |

---

## 📈 Proyectos Recientes

### [ci-actionsMDB](https://github.com/marcdb22/ci-actionsMDB)
Repositorio destinado al desarrollo de una calculadora automatizada mediante flujos de trabajo de Integración Continua.

* **Estado del Pipeline:** [![CI MDB](https://github.com/marcdb22/ci-actionsMDB/actions/workflows/ci.yml/badge.flow.svg)](https://github.com/marcdb22/ci-actionsMDB/actions/workflows/ci.yml)
* **Características:** Pruebas unitarias multi-versión automatizadas (PHP 8.1, 8.2, 8.3) y exportación de artefactos JUnit.

---

## 💻 Demostración de Código (PHP)

Ejemplo de implementación limpia y documentada utilizando buenas prácticas:

```php
/**
 * Calcula la división de dos valores numéricos.
 * @throws Exception Si el divisor es equivalente a cero.
 */
public function divisio($a, $b) {
    if ($b == 0) {
        throw new Exception("No es pot dividir per zero.");
    }
    return $a / $b;
}