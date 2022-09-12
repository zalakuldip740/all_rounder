/// Failure
///
/// common failure class for all type of errors
class Failure {
  final String statusCode;
  final String? message;
  final dynamic exception;

  const Failure({required this.statusCode, this.message, this.exception});
}
