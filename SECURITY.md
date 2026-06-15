# Política de Seguridad

## 📋 Versión

**Última actualización**: Junio 2026

## 🔒 Descripción

Este documento describe las medidas de seguridad implementadas en el sitio web de SEPREVIN para proteger la información de los usuarios y mantener la integridad del sitio.

## 🛡️ Medidas de Seguridad Implementadas

### Headers HTTP de Seguridad

| Header | Valor | Propósito |
|--------|-------|-----------|
| `X-Content-Type-Options` | `nosniff` | Previene MIME sniffing |
| `X-Frame-Options` | `DENY` | Previene clickjacking |
| `X-XSS-Protection` | `1; mode=block` | Protección contra XSS |
| `Referrer-Policy` | `strict-origin-when-cross-origin` | Control de información del referer |
| `Permissions-Policy` | Restringido | Limita acceso a APIs sensibles |
| `Strict-Transport-Security` | `max-age=31536000` | Fuerza HTTPS |

### Content Security Policy (CSP)
