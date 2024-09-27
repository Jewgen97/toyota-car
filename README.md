# toyota-car
def count_toyota_cars(cars):
    count = 0
    for car in cars:
        if car['brand'].lower() == 'toyota':  # Assuming 'brand' is a key in your car data
            count += 1
    return count

# Example usage:
car_data = [
    {'brand': 'Toyota', 'model': 'Camry'},
    {'brand': 'Toyota', 'model': 'Corolla'},
    {'brand': 'Honda', 'model': 'Civic'},
    {'brand': 'Ford', 'model': 'Fusion'},
    {'brand': 'Toyota', 'model': 'RAV4'}
]

toyota_count = count_toyota_cars(car_data)
print("Number of Toyota cars:", toyota_count)
 count = 0

