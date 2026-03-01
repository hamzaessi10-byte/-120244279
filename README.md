public class SpatialCalculator {
    // دالة لحساب المساحة المتاحة للعرض بناءً على أبعاد الحائط
    public double calculateMaxScreenSize(double wallWidth, double wallHeight) {
        double safeMargin = 0.20; // ترك 20% هامش أمان
        return (wallWidth * wallHeight) * (1 - safeMargin);
    }
}
